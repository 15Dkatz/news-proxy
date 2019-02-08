## A proxy around the Hacker news API

The Hacker News API is great. It returns all the latest and greatest stories/articles in the tech indstury. However, it's top stories request returns a list of the internal ids for each story. Then, to get the full story information, you have to make a request one story at a time within the list. That's more work than I feel necessary, so I wrapped up the requests for the top 10 stories in a custom /topstories request.

Try it out:
[https://news-proxy-server.appspot.com/topstories](https://news-proxy-server.appspot.com/topstories)