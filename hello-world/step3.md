API

Add user

update influxdb config

API way

`curl -i -XPOST "http://localhost:8086/write?db=mydb" --data-binary 'meters,meter=cpu load=4'`{{execute}}
`curl -G 'http://localhost:8086/query?db=mydb' --data-urlencode 'q=select * from server'`{{execute}} 
