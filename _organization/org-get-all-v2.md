---
title: Get All Organizations
position: 5
description: Retrieve a list of all organizations, including the number of accounts assigned to them.
type: get
endpoint: https://chapi.cloudhealthtech.com/v2/organizations
parameters:
  - name: per_page
    required: no
    content: Specify how many results should be displayed per page. Default value is 30. Maximum value is 100.
  - name: page
    required: no
    content: Specify the page number for results.
right_code_blocks:
  - code_block: |-
      curl --request GET -H 'Authorization: Bearer <your_api_key>' -H 'Content-Type: application/json' -d
          'https://chapi.cloudhealthtech.com/v2/organizations'
    title: Sample Request
    language: bash
---
