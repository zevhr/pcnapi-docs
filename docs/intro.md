# Introduction to the PCNAPI
The PCNAPI is a Node.js API developed by Awex.<br>
This API is ready to return Player Data to be formatted however you like.

### Rate Limits
Our API rate limits by the hour. For now, it is 100rqs/h. We plan to lower this to 100rqs/m soon and raise the threshhold for authorized users.

### Errors
The API should be returning 404s when you error out. However, if you run into infinite queries, you may have ran a non-existent query. Please make sure your query was correct before [contacting us](https://plaguecraft.xyz/contact)