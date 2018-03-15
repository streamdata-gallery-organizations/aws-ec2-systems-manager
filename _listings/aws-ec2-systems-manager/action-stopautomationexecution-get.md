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
  /?Action=StopAutomationExecution&k=1:
    get:
      summary: ' Stop Automation Execution '
      description: Stop an Automation that is currently executing
      operationId: stopAutomationExecution
      parameters:
      - in: query
        name: AutomationExecutionId
        description: The execution ID of the Automation to stop
        type: string
      responses:
        200:
          description: OK
      tags:
      - stop
      - automation
      - execution
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