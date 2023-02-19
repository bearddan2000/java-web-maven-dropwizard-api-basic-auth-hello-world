# java-web-maven-dropwizard-api-basic-auth-hello-world

## Description
A POC for dropwizard api with basic authentication.

## Tech stack
- java
- maven
  - dropwizard

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- Endpoints
  - curl localhost/hello-world -u "<user>:<password>"
| user | password |
|------|----------|
| user | password |
| guest | password |
| admin | password |

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code based on](https://howtodoinjava.com/dropwizard/dropwizard-basic-auth-security-example/)
