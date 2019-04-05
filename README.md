
# Nube Naming Conventions

### Example namimg


point name: zone_temp

#### type
```zone, temp, droplet, fcu, point```

#### refTags
```zoneRef:@room_a, equipRef:@fcu_1, siteRef:@124254345, siteName:@seaforth, stateRef@:nsw```



### example using tags

```
point name:  UI1 (Is not changed)
tags: fan, status, ac, sensor

```
##### ref's

```
equipRef: 1B
siteRef: Seaforth
client: CBA
stateRef: NSW

```

## Examples

```ra_fan_status```

```sa_fan_status```



# nube-tags

## Ref to exel sheet for tags
https://docs.google.com/spreadsheets/d/1nk6Beu72GDU_h88nAiTzUfH6loXkUQLbimr9UmgNaEk/edit#gid=1119675202

https://docs.google.com/spreadsheets/d/1nXWotLvyqipxYz8wp2lihJ0WT8vHFGQlQ9IRXMwyPr4/edit#gid=1813800346

## SQL Tags
Tagging os for having an association for meta data with time series data 
Project Haystack

Tags are based of the haystack tagging format

https://project-haystack.org/

### SQL Tags blog example 
http://elliot.land/post/handling-tags-in-a-sql-database


### Simple Tagging Example 
#### Example

##### Car tags
```Tyers,  Motor, Petrol Type, Colour```


##### Motorbike tags
```Tyers,  Motor, Petrol Type, Colour```

### SQL Query example

```Select “Tyers”, “Colour” from tags data```


