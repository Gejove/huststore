## ttl ##

**Interface:** `/hustcache/ttl`

**Method:** `GET`

**Parameter:** 

*  **key** (Required)  

**Sample A:**

    curl -i -X GET "http://localhost:8085/hustcache/ttl?key=test_key"

**Result A1:**

	HTTP/1.1 404 Not Found

**Result A2:**

	HTTP/1.1 200 OK
	Content-Length: 2
	Content-Type: text/plain

	45
	
[Previous](../hustcache.md)

[Home](../../../index.md)