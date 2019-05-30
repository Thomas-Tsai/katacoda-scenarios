API

Add user

update influxdb config

API way

`curl -i -XPOST "http://localhost:8086/write?db=userdb1&u=user1&p=influxpass" --data-binary 'server1,meter=cpu load=4'`{execute}}
`curl -G 'http://localhost:8086/query?db=userdb1&u=user1&p=influxpass' --data-urlencode 'q=select * from server'`{{execute}} 
