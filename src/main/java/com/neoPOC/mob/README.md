# MOB Examples

## Procedures


### Verification
The procedures in this project should be listed
as available procedures using the following command

```javascript 1.5


CALL dbms.procedures() yield name
WHERE name starts with 'com.neoPOC' 
RETURN name
ORDER BY name
```


![Sample Image](../../../images/sample.png)
Format: ![Alt Text](url)