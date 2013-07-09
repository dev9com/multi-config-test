multi-config-test
=================

Maven-based Example of Multi-Build Configuration

This simple project is intended to help explore the configuration of multi-builds in a CI environments (such as Jenkins or TeamCity).

It includes a Maven POM, preconfigured to run a build with multiple threads and SLF4J logging.  The test cases pick up both Selenium/Sauce Labs configuration as well as a user-defined sample property.

For more information on the Sauce Labs / Jenkins plugin, see:

https://saucelabs.com/docs/jenkins
