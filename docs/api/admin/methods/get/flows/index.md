---
layout: api
title: GET /flows
---

Get the active flow configuration.

Requires permission: <code>flows.read</code>

### Headers

Header          | Value
----------------|-------
`Authorization` | `Bearer [token]` - if authentication is enabled

### Response

Status Code | Reason         | Response
------------|----------------|--------------
`200`       | Success        | An array of node objects. See example response body
`401`       | Not authorized | _none_

{% highlight json %}
[
  {
    "type": "tab",
    "id": "396c2376.c693dc",
    "label": "Sheet 1"
  }
]
{% endhighlight %}
