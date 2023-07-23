# sqlserver-ssl-web-adminer

## Description
Creates a small database table
called `dog`.

Sql server uses self-signed ssl.

## Tech stack
- phpAdmin
- ms sql

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- adminer

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
