This is a sample project of [TIBCO BusinessEvents](https://docs.tibco.com/products/tibco-businessevents-5-2-0).  It illustrates the use of various data types in TIBCO BusinessEvents (BE) applications.  The main purpose of this project is, however, to demonstrate a framework for testing BE applications.

## Unit test framework for TIBCO BusinessEvents

To support Test-Driven development (TDD) and Continuous Delivery (CD), we need a test framework to automate the unit tests for individual rules and rule-functions in BE applications.  This project illustrates a light-weight framework for developers to write unit tests within the same BE application project, and expose all tests as a uniform REST API.  The sister project [beunit](https://github.com/yxuco/beunit) illustrates how to use [JUnit](http://junit.org/) to run tests and collect test results via the REST API of this test framework.  With the help of [Maven](https://maven.apache.org/) and [Jenkins](https://jenkins-ci.org/), we can include the unit test as a step in the CD process.

## Prerequisites

It is tested with TIBCO BusinessEvents 5.2.0, but the framework may work with earlier version of BE as well.  If you are a licensed TIBCO customer, you can download and install the following BE packages from [TIBCO eDelivery](https://edelivery.tibco.com):
 - [TIBCO BusinessEvents Standard Edition](https://edelivery.tibco.com/storefront/eval/tibco-businessevents-standard-edition/prod10052.html)
 - [TIBCO BusinessEvents Data Modeling](https://edelivery.tibco.com/storefront/eval/tibco-businessevents-data-modeling/prod10354.html)
 - [TIBCO BusinessEvents Decision Manager](https://edelivery.tibco.com/storefront/eval/tibco-businessevents-decision-manager/prod10355.html)
 - [TIBCO BusinessEvents Stream Processing](https://edelivery.tibco.com/storefront/eval/tibco-businessevents-event-stream-processing/prod10353.html)
 
## Install and configure
 
Description of setting-up the sample will come here ...

## The author

Yueming is a Sr. Architect working at [TIBCO](http://www.tibco.com/) Architecture Service Group.