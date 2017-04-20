---
Title: Java SDK Examples
Category: technical
permalink: Kount-Java-SDK/java-sdk-examples
---

A list of examples follow now:
* Example 1: some item added, request fired
```
   Inquiry inq = new Inquiry();
   inq.setMerchantId("merchant");
   
   // more things follow

   KountRisClient client = new KountRisClient(new URL("http://some.url.be", "put-the-jwt-key-here");
   Response response = client.process(inq);
   System.out.println(response.toString());
```
* Example 2: dumb

