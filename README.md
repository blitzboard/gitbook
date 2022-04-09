# Overview

![](.gitbook/assets/image\_logo.png)

Blitzboard is an open-source web tool to create custom dashboards for visualizing complex information, which may include relationships, dependencies, locations, and time. You can easily edit the data and configure its layouts, icons, labels, and more.&#x20;

![](.gitbook/assets/image\_1.png)

**Property Graph** is a data model which can represent complex information, and [PG format](https://pg-format.readthedocs.io/en/0.3/contents/pg-format.html) is a text serialization for property graph datasets&#x20;

`example.pg`

```
# NODES
101  :person  name:Alice  country:"United States"
102  :person  :student  name:Bob  country:Japan
# EDGES
101  -- 102  :same_school  :same_class  since:2012
101  -> 102  :likes  since:2015
```

Blitzboard can maintain multiple dashboards with their respective visualization configurations, moreover, connect to databases to retrieve real-time information.

![](<.gitbook/assets/image\_2 (1).png>)
