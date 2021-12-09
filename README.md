# java-cli-maven-surefire-findbugs-junit-test-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using JUnit
framework with surefire plugin.

## Tech stack
- java
- maven
	- findbugs
  - junit
  - surefire

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/maven-modules/maven-integration-test)
