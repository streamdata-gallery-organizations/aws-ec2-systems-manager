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
  /?Action=ListInventoryEntries&k=1:
    get:
      summary: ' List Inventory Entries '
      description: A list of inventory items returned by the request
      operationId: listInventoryEntries
      parameters:
      - in: query
        name: Filters
        description: One or more filters
        type: string
      - in: query
        name: InstanceId
        description: The instance ID for which you want inventory information
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: TypeName
        description: The type of inventory item for which you want information
        type: string
      responses:
        200:
          description: OK
      tags:
      - list
      - inventory
      - entries
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