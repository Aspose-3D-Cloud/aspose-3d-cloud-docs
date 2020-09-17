---
title: "Convert file between formats using saveOptions parameter"
type: docs
url: /convert-file-between-formats-using-saveoptions-parameter/
weight: 20
---

# **Introduction**
Aspose.3D Cloud allows you to convert a file between formats using the saveOptionParameter. The Aspose.3D Cloud API provides the following methods
### **API Information**

|**API**|**Type**|**Description**|**Swagger Link**|
| :- | :- | :- | :- |
|/3d/saveas/saveoption|POST|Convert to a new Format|[PostConvertByOpt](https://apireference.aspose.cloud/3d/#/OpenSave/PostConvertByOpt)|
The SaveFormat parameter can take the following values

|**Value**|**Save Format**|
| :- | :- |
|AMFSaveOption |0|
|ColladaSaveOption |1|
|ColladaSaveOption |2|
|DracoSaveOption |3|
|FBXSaveOption |4|
|GLTFSaveOption |5|
|ObjSaveOption |6|
|PdfSaveOption |7|
|PlySaveOption |8|
|RvmSaveOption |9|
|STLSaveOption |10|
|U3DSaveOption |11|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

 curl -X POST "https://api.aspose.cloud/v3.0/3d/saveas/saveoption?name=Aspose3D.pdf&newfilename=tester.pdf&IsOverwrite=true" -H "accept: application/json" -H "authorization: Bearer eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYmYiOjE1NzE1MTg2NDUsImV4cCI6MTU3MTYwNTA0NSwiaXNzIjoiaHR0cHM6Ly9hcGkuYXNwb3NlLmNsb3VkIiwiYXVkIjpbImh0dHBzOi8vYXBpLmFzcG9zZS5jbG91ZC9yZXNvdXJjZXMiLCJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXSwiY2xpZW50X2lkIjoiNzg5NDZmYjQtM2JkNC00ZDNlLWIzMDktZjllMmZmOWFjNmY5IiwiY2xpZW50X2lkU3J2SWQiOiIiLCJzY29wZSI6WyJhcGkucGxhdGZvcm0iLCJhcGkucHJvZHVjdHMiXX0.AHT0p9Fm2fDv5veCN73VAVgE9OEvduRNXp3btWXqIFckF1sgIv6aBnxBCRtnYzFP9iw9xJm0i09LbpPA89VoxSCAIQ5FfRarOBMUz_mDH_tI2PO1eMd8XRdIYamAloNh0fi0wje7y5NyR41IV5VWhxMcPeYI6Q0yyVzMzmRIuTkY9ApK7sUY4rXXamWF4xgeT5spY9CFYuAZu-6Ivh2IGLqvvMPHwC28TLX4_oDSlnocAPcwbIz_16UUjtBC8nZWdsm_0375wDK0h9M3oDwalu0NbnzHukarVuHuEA0ceSi1muhCC_ZNJnqbbwlFSClr2lZdqGyeeyvcQeX2F7nwAg" -H "Content-Type: application/json" -d "{\t\"FileContentType\": null,\t\"FlipCoordinate\": null,\t\"VertexElement\": null,\t\"PositionComponents\": [\"x\", \"y\", \"z\"],\t\"FaceElement\": null,\t\"FaceProperty\": null,\t\"SaveFormat\": 8,\t\"FileSystem\": {\t\t\"FileSystemType\": 0,\t\t\"Directory\": null\t},\t\"LookupPaths\": null,\t\"FileName\": null,\t\"FileFormat\": null,\t\"directory\": null}"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

 NO CONTENT

```

{{< /tab >}}

{{< /tabs >}}
### **SDK Example**
{{< tabs tabTotal="2" tabID="4" tabName1="C#" tabName2="Java" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "562f676098edf247d40c311d2e4414c9" "PostConvertByOptExample.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "562f676098edf247d40c311d2e4414c9" "postConvertByFormatExample.java" >}}

{{< /tab >}}

{{< /tabs >}}
