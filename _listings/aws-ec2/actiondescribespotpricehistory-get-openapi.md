---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Describe Spot Price History
  version: 1.0.0
  description: Describes the Spot price history.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeSpotFleetRequestHistory:
    get:
      summary: Describe Spot Fleet Request History
      description: Describes the events for the specified Spot fleet request during
        the specified time.
      operationId: describespotfleetrequesthistory
      x-api-path-slug: actiondescribespotfleetrequesthistory-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,       and provides an error response
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return in a single call
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of results
        type: string
      - in: query
        name: SpotFleetRequestId.N
        description: The IDs of the Spot fleet requests
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Fleet Request History
  /?Action=DescribeSpotPriceHistory:
    get:
      summary: Describe Spot Price History
      description: Describes the Spot price history.
      operationId: describespotpricehistory
      x-api-path-slug: actiondescribespotpricehistory-get
      parameters:
      - in: query
        name: AvailabilityZoneGroup
        description: The user-specified name for a logical grouping of bids
        type: string
      - in: query
        name: BlockDurationMinutes
        description: The required duration for the Spot instances (also known as Spot
          blocks), in minutes
        type: string
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier that you provide to ensure
          the idempotency of the request
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceCount
        description: The maximum number of Spot instances to launch
        type: string
      - in: query
        name: LaunchGroup
        description: The instance launch group
        type: string
      - in: query
        name: LaunchSpecification
        description: Describes the launch specification for an instance
        type: string
      - in: query
        name: SpotPrice
        description: The maximum hourly price (bid) for any Spot instance launched
          to fulfill the request
        type: string
      - in: query
        name: Type
        description: The Spot instance request type
        type: string
      - in: query
        name: ValidFrom
        description: The start date of the request
        type: string
      - in: query
        name: ValidUntil
        description: The end date of the request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Spot Price History
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