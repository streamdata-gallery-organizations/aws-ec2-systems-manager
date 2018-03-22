---
swagger: "2.0"
info:
  title: AWS EC2 Systems Manager API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeActivations:
    get:
      summary: ' Describe Activations '
      description: |-
        Details about the activation, including: the date and time the activation was created,
           the expiration date, the IAM role assigned to the instances in the activation, and the number of
           instances activated by this registration
      operationId: describeActivations
      parameters:
      - in: query
        name: Filters
        description: A filter to view information about your activations
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: A token to start the list
        type: string
      responses:
        200:
          description: OK
      tags:
      - activations
definitions: []
x-collection-name: AWS EC2 Systems Manager
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---