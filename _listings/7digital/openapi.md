swagger: "2.0"
x-collection-name: 7digital
x-complete: 1
info:
  title: 7digital Purchasing API
  description: the-purchasing-api-allows-3rd-parties-to-deliver-digital-content-to-individual-users-
  version: "1.2"
host: api.7digital.com
basePath: 1.2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  user/purchase/{purchaseid}/track/{trackid}:
    'delete ':
      summary: user/purchase/{purchaseid}/track/{trackid}
      description: This method allows a user to remove a purchase of a track from
        the sales report when the purchase has been refunded.
      operationId: userpurchasepurchaseidtracktrackid
      x-api-path-slug: userpurchasepurchaseidtracktrackid-delete
      parameters:
      - ~
      - in: query
        name: purchaseid
        description: purchase id identifying the transaction at 7digitals end that
          the refunded item belongs to
      - in: query
        name: trackid
        description: nttttttttThe 7digital id of the track being refundednnttttttt
      responses:
        200:
          description: OK
      tags:
      - User
      - Purchase
      - Purchaseid
      - Track
      - Trackid