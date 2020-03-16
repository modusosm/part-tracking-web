This HTML has to be served from a web server because of the REST call (CORS doesn't like it run locally).  Feel free to use any web server you like.  I'm using this: https://www.npmjs.com/package/http-server

./index.html is a bar chart showing inventory for every catalog part at every operation

./index_filtered.html is the same chart but filtered for `at_operation == null`. `null` should represent parts that are fully completed and ready for consumption.
