---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /countries:
    get:
      summary: Get Countries
      description: Retrieve a list of country codes with corresponding subregions
      operationId: getCountries
      x-api-path-slug: countries-get
      responses:
        200:
          description: OK
      tags:
      - Countries
  /my/account:
    get:
      summary: Get My Account
      description: Get account details
      operationId: getMyAccount
      x-api-path-slug: myaccount-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Account
    put:
      summary: Put My Account
      description: Update account details
      operationId: putMyAccount
      x-api-path-slug: myaccount-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - My
      - Account
  /my/counts:
    get:
      summary: Get My Counts
      description: Get your actionable status counts
      operationId: getMyCounts
      x-api-path-slug: mycounts-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Counts
  /my/negotiations/{id}/counter:
    post:
      summary: Post My Negotiations Counter
      description: Post my negotiations counter.
      operationId: postMyNegotiationsCounter
      x-api-path-slug: mynegotiationsidcounter-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - My
      - Negotiations
      - Id
      - Counter
  /accounts:
    post:
      summary: Post Accounts
      description: Create an account.
      operationId: postAccounts
      x-api-path-slug: accounts-post
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Accounts
---