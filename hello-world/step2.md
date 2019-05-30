Write data to influxdb

`insert <measurement>[,<tag-key>=<tag-value>...] <field-key>=<field-value>[,<field2-key>=<field2-value>...] [unix-nano-timestamp] `

`INSERT meters,meter=gas,place=6F-1 volume=123.456,consumption=5`{{execute}}

Read data from Influxdb

`SELECT INTEGRAL( [ * | <field_key> | /<regular_expression>/ ] [ , <unit> ]  ) [INTO_clause] FROM_clause [WHERE_clause] [GROUP_BY_clause] [ORDER_BY_clause] [LIMIT_clause] [OFFSET_clause] [SLIMIT_clause] [SOFFSET_clause] `

`select * from "meters"`{{execute}}

`exit`{{execute}}

