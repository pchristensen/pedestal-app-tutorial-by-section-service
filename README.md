# tutorial-service

I worked through the excellent [Pedestal App Tutorial](https://github.com/pedestal/app-tutorial/wiki).

The repo for the Cognitect version is tagged by tutorial page, but there are often 2-5 sections per page,
and a lot of code per diff. In this repo, there's one commit per section. Also, the commits are by section
name, not version number. There aren't many commits in this repo because most of the work was in the
accompanying pedestal app project, [pedestal-app-tutorial-by-section](https://github.com/pchristensen/pedestal-app-tutorial-by-section)

My notes on the Pedestal Tutorial
- [Pedestal Tutorial Notes Part 1](http://pchristensen.com/blog/articles/pedestal-tutorial-part-1-notes/)
- [Pedestal Tutorial Notes Part 2](http://pchristensen.com/blog/articles/pedestal-tutorial-part-2-notes/)

## Getting Started

1. Start the application: `lein run-dev` \*
2. Go to [localhost:8080](http://localhost:8080/) to see: `Hello World!`
3. Read your app's source code at src/tutorial_service/service.clj. Explore the docs of functions
   that define routes and responses.
4. Run your app's tests with `lein test`. Read the tests at test/tutorial_service/service_test.clj.
5. Learn more! See the [Links section below](#links).

\* `lein run-dev` automatically detects code changes. Alternatively, you can run in production mode
with `lein run`.

## Configuration

To configure logging see config/logback.xml. By default, the app logs to stdout and logs/.
To learn more about configuring Logback, read its [documentation](http://logback.qos.ch/documentation.html).

## Links
* [Other examples](https://github.com/pedestal/samples)
