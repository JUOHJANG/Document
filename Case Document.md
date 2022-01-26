[MOCOCO]KnowlegedBase-001

## 증상(Symptom)
In MicroStrategy Enterprise Manager 10.x various errors or issues may occur when performing the Data Load including Primary Key Violation database errors, 
unexpected database locks, missing data from the Enterprise Manager tables, and other Data Load failures.

## 원인(Cause)
One potential cause for this behavior is having multiple Enterprise Manager services configured to access the same Enterprise Manager warehouse.The Enterprise Manager environment is designed to have one running service per warehouse.  

## 유형(Type)
 - 결함(Defect)
 - 기능개선(Function Improvement)

## 조치사항(Action)
Ensure that each Enterprise Manager warehouse has only a single Enterprise Manager service configured to access it. 

## 배포 시점(Release Time)
 - Next Version (major version -> v 2.0) 
 - Hot Fix (minor version -> v 1.1)
 

