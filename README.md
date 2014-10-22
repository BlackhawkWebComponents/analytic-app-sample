analytic-app-sample
================

    git clone https://github.com/BlackhawkWebComponents/analytic-app-sample.git
    cd analytic-app-sample
    bower install
    serve up in whatever http server like python: http-server .

* Assumes local solr default install with cors enabled and sample data loaded running at: http://localhost:8983/solr/collection1
* If you want to change the url of solr, modify components/analytic-elements/app-globals.html
* TODO: app-globals should be configurable in this root application
* Edit sampleData.js to change dashboard configuration