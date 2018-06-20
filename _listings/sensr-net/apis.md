---
name: Sensr.net
x-slug: sensr-net
description: Sensr.net keeps track of interesting images and alert you when something
  happens. Were starting off with basic motion detection. We keep the images around
  and organize them by time and day. Well send you an email or a text message if youd
  like when ...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/924-sensr-net.jpg
x-kinRank: "7"
x-alexaRank: "766070"
tags: Sensr.net
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sensr-net/master/_listings/sensr-net/apis.md
specificationVersion: "0.14"
apis:
- name: Devices API Creating a device
  x-api-slug: devices-api
  description: |-
    You can create new devices via the API, useful if you want to automatically provision new devices and start monitoring automatically.
    This API method is used by our Puppet manifest, Chef cookbook and installer shell script to automatically create devices during the agent installation.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/924-sensr-net.jpg
  humanURL: https://sensr.net/api
  baseURL: ://api.serverdensity.io.///inventory/devices
  tags: Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sensr-net/master/_listings/sensr-net/inventorydevices--openapi.md
- name: Devices API Updating a device
  x-api-slug: devices-api
  description: Update a device and the associated metadata.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/924-sensr-net.jpg
  humanURL: https://sensr.net/api
  baseURL: ://api.serverdensity.io.///inventory/devices/deviceId
  tags: Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sensr-net/master/_listings/sensr-net/inventorydevicesdeviceid--openapi.md
- name: Devices API View device by agent key
  x-api-slug: devices-api
  description: View device by agent key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/924-sensr-net.jpg
  humanURL: https://sensr.net/api
  baseURL: ://api.serverdensity.io.///inventory/devices/agentKey/byagentkey
  tags: Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sensr-net/master/_listings/sensr-net/inventorydevicesagentkeybyagentkey--openapi.md
- name: Devices API
  x-api-slug: devices-api
  description: Sensr.net keeps track of interesting images and alert you when something
    happens. Were starting off with basic motion detection. We keep the images around
    and organize them by time and day. Well send you an email or a text message if
    youd like when ...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/924-sensr-net.jpg
  humanURL: https://sensr.net/api
  baseURL: ://api.serverdensity.io./
  tags: Sensr.net
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sensr-net/master/_listings/sensr-net/openapi.md
x-common:
- type: x-website
  url: https://sensr.net/api
- type: x-blog
  url: http://sensr.net/blog
- type: x-blog-rss
  url: http://sensr.net/blog/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sensr-net
- type: x-crunchbase
  url: https://crunchbase.com/organization/sensr-net
- type: x-documentation
  url: https://api.sensr.net/doc/v3/index.html
- type: x-twitter
  url: https://twitter.com/sensr
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---