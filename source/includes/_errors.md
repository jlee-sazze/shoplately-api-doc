# Errors

<aside class="notice">This error section is stored in a separate file in `includes/_errors.md`. Slate allows you to optionally separate out your docs into many files...just save them to the `includes` folder and add them to the top of your `index.md`'s frontmatter. Files are included in the order listed.</aside>

The Kittn API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Something is wrong with the request
401 | Unauthorized -- Your API key is wrong
403 | Forbidden --
404 | Not Found --
405 | Method Not Allowed --
406 | Not Acceptable --
410 | Gone --
429 | Too Many Requests -- You're requesting too many API
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
