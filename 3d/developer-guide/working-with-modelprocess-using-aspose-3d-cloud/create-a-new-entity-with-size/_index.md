---
title: "Create a new entity with size"
type: docs
url: /create-a-new-entity-with-size/
weight: 10
---

# **Introduction**


Aspose.3D Cloud allows you to add a new entity with size. The API support the following entity types:

- Box
- Cylinder
- Sphere
- Torus
- Plane

The Aspose.3D Cloud API provides the following methods
### **API Information**

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/3d/root|POST|Create a new Entity|[PostModel](https://apireference.aspose.cloud/3d/#/ModelProcess/PostModel)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

**Request**

```java

 curl -X POST "https://api.aspose.cloud/v3.0/3d/root?name=Aspose3D.pdf&newformat=pdf" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NzEzMDM4MjAsImV4cCI6MTU3MTM5MDIyMCwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.cRdWGHMKANFDBgrk7ztxWuTVEP5S5K7g5NA0ChHn_TOTLCb9LY0nR-WFjDSrDzWVanXJBKjn-JSdfaSOJhtkfYoTmXp2GsTtSl81txAp7_2LVJivVEdwVREnDBPlI8OBtNT8ZXfg4iYXjkrwqe2ZYqnRXtDDizXNoFlN-4KqBxqM9nu2Cf3SI35-qCmqBPEikSfJnYYX8T04Y6ZfhOJWMbvVMXJGJnjHhZGw8dHkssVv00qw-whyvZxAHFAyVaMIndJtMYHc7ypu5R4V-Gw9eNd9R1IbEgSQfDp9Onhu5qq4a_2-FN-3T0-Xr9I1BX_Z46SYLI36WJJr77Us3PdJFQ" -H "Content-Type: application/json" -d "{ \"Type\": \"string\", \"Transform\": { \"Translation\": { \"x\": 100, \"y\": 100, \"z\": 100, \"Length2\": 0, \"Length\": 0 } }, \"Entity\": { \"Type\": \"string\", \"Torus\": { \"Name\": \"string\", \"Radius\": 10, \"Tube\": 20, \"RadialSegments\": 10, \"TubularSegments\":10, \"Arc\": 10 } }}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 content

```

{{< /tab >}}

{{< /tabs >}}
### **SDK Example**
{{< tabs tabTotal="1" tabID="4" tabName1="C#" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "562f676098edf247d40c311d2e4414c9" "PostModelExample.cs" >}}

{{< /tab >}}

{{< /tabs >}}
