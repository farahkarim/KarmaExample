# clinicalRec.json

## Add Column

## Add Node/Literal

## PyTransforms
#### _persontreatment_
From column: _receivesTreatment / treatmentID_
``` python
return getValue("treatmentID")
```


## Selections

## Semantic Types
| Column | Property | Class |
|  ----- | -------- | ----- |
| _patientID_ | `uri` | `iasis:LCPatient1`|
| _persontreatment_ | `iasis:birthday` | `iasis:LCPatient1`|
| _sex_ | `iasis:gender` | `iasis:LCPatient1`|
| _treatmentDate_ | `iasis:tDate` | `iasis:LCTreatment1`|
| _treatmentID_ | `uri` | `iasis:LCTreatment1`|


## Links
| From | Property | To |
|  --- | -------- | ---|
