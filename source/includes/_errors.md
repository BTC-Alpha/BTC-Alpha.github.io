# HTTP Errors

HTTP API uses following error statuses:

Error Code | Meaning
---------- | -------
400 | Bad Request -- Something wrong with input data. See response body for mode details. Also check API documentation.
401 | Unauthorized -- Your API key is wrong. Check publick and secret keys, check auth headers.
403 | Forbidden -- Forbidden to process method with specified parameters. 
404 | Not Found -- Method or resource not found.
405 | Method Not Allowed -- Check HTTP method for specified endpoint.
406 | Not Acceptable -- You requested a format that isn't json.
429 | Too Many Requests -- You're requesting fast! Slow down! See documentation for more details.
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarially offline for maintanance. Please try again later.
