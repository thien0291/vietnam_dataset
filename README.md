# vietnam_dataset
Dataset about province/city, district, ward, street in Vietnam  
Updated in March 2019  

## Structures  

- Index.JSON
- data
|- SG.JSON
|- HN.JSON
|- ...

Data:  
- Province with name / code
- Districts inside province
- Wards inside district
- Streets inside ward  

This data maybe too big for direct loading so it's seperated for multiple json files. Each json file represent for a province. All index data is stored in Index.json  

You can fetch / ajax call with jsdelivr CDN with the pattern in the end of this file.  


## CDN Supported  

### for index  
```https://cdn.jsdelivr.net/gh/thien0291/vietnam_dataset@1.0.0/Index.json``` 

### for a province (ex: Ho Chi Minh City)
```https://cdn.jsdelivr.net/gh/thien0291/vietnam_dataset@1.0.0/data/SG.json```  
  






