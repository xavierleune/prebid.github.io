---
layout: bidder
title: Optimatic
description: Prebid Optimatic Bidder Adaptor
hide: true
biddercode: optimatic
biddercode_longer_than_12: false
media_types: video
---

### Note:

Optimatic adapter only supports video ads.

### bid params

{: .table .table-bordered .table-striped }
| Name        | Scope    | Description            | Example          | Type     |
|-------------|----------|------------------------|------------------|----------|
| `placement` | required | Optimatic Placement ID | `'2chy7Gc2eSQL'` | `string` |
| `bidfloor`  | required | Bid floor              | `2.00`           | `float`  |
