install influxdb

`apt-get update`{{execute}}

`apt-get install influxdb`{{execute}}

Install client

`apt-get install influxdb-client `{{execute}}

Use influxdb client

`influx`{{execute}}

Display Databases

`show databases`{{execute}}

Create Database

1. creat database only

`create database mydb`{{execute}} 

2. write data and database

`INSERT meters,meter=gas,place=6F-1 volume=123.456,consumption=3`{{execute}} 
