# Errors

<!-- <aside class="notice">
This error section is stored in a separate file in <code>includes/_errors.md</code>. Slate allows you to optionally separate out your docs into many files...just save them to the <code>includes</code> folder and add them to the top of your <code>index.md</code>'s frontmatter. Files are included in the order listed.
</aside> -->

The WordToken API uses HTTP response status codes to indicate the success or failure
of your API request. If your request fails, WordToken will return an Error object containing the appropriate status code.

Generally, the status code will fall under 3 categories:

2xx for successful requests.</br>
4xx for client side errors.</br>
5xx for errors resulting from servers that host the WordToken API.

## HTTP Status Codes

Error Code | Meaning
---------- | -------
200 | OK: Successful request. 
400 | Bad Request: Results when using an invalid url syntax.
401 | Unauthorized: This error will return if a request is made without a developer API key.
404 | Not Found: You've requested a resource that doesn't or no longer exists.
429 | Too Many Requests: Requests rates are limited by API Key, this error will be returned if you exceed the limit.
500+ | Server issues. This is on us.