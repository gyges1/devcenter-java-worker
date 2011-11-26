# Run Java worker processes on Heroku

Any business application today has two components to it:

1. A web component that is consumed by the end-user
2. A non-web component to supplement your web component.

The non-web component of your application is called a "worker" process in Heroku.  This article is going to talk about getting started on the running a Java worker process in your Heroku environment.

## Prerequisites

* Basic Java knowledge, including an installed version of the JVM and Maven.
* Basic Git knowledge, including an installed version of Git.
* A Java web application. If you don't have one follow the first step to create an example. Otherwise skip that step.
