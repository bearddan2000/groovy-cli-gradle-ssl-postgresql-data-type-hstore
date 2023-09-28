# groovy-cli-gradle-ssl-postgresql-data-type-hstore

## Description
Creates a small table `dog` that uses
a key value pair data type.

Uses self-sign ssl.

## Tech stack
- groovy
- gradle
  - log4j
  - postgresql driver

## Docker stack
- alpine:edge
- postgresql:alpine
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[HStore data type info](https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-hstore/)
