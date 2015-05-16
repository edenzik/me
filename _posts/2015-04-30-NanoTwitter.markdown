We present Eden's and Jacob's NanoTwitter, a project for COSI 105b at Brandeis University (Spring 2015).

We set out to create a simplified version of Twitter that can withstand the test of scale. The purpose of the exercise was to demonstrate a variety of scaling techniques that were covered in the class - and put them into practice under controlled testing conditions in a live application.

We used the Sinatra Ruby web framework to handle the server component, with Postgres for persistence and Redis for caching.

AJAX technologies like Javascript and jQuery were used in the front end to ensure good user experience, and good user interface design guidelines were followed to make an intuitive product - such that anyone who uses Twitter can enjoy the basic feature set of NanoTwitter.

The name of the class is "Software Engineering and Architecture to Scale", and indeed - the major focus of this product was the ability to scale up and be capable of handling a large amount of simultaneous users. We used the load testing utility loader.io to provide reliable and consistent load testing data, effectively enabling us to run multiple tests following any change to the system, to see a change in responsiveness.

By validating performance changes to the system, we were able to effectively have an incremental approach to scaling.

All aspects of the application, its architecture, and its interface are given below.

Most importantly, the approaches we used for scaling, as well as their results, are given in detail here.
