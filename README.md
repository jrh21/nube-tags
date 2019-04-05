
# Nube Naming Conventions

### Example namimg not using tags

point name: fan_Status_ACU_1B

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

```fan_Status```

``Fan_Status``

```ac_Fan_Status```

``ac_fan_Status``

``acFanStatus``

fan_Status_ACU_1B

Or 

fanStatus

or 

Fan_Status

or Fan Status




# nube-tags

## Ref to exel sheet for tags
https://docs.google.com/spreadsheets/d/1nk6Beu72GDU_h88nAiTzUfH6loXkUQLbimr9UmgNaEk/edit#gid=1119675202

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


