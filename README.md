# java-cli-buildr-ssl-postgresql-data-type-enum

## Description
Creates a small database table
called `dog`. Uses an enum user defined type.

Uses self-sign ssl.

## Tech stack
- java
- buildr
  - 6.8.2

## Docker stack
- alpine:edge
- postgresql:alpine
- vanto/apache-buildr:latest-jruby-jdk8

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
