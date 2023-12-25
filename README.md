<div align="center">
 
  <h1> MEDICAL RECORD SYSYTEM MAINTAINANCE USING JAVA AND Oracle</h1>
 
 
</div>
 
# Introduction
- This program's objective is maintenance of medical records using JAVA-Jswing and ORACLE-Database Management.
 
- Additionaly, this program offers graphical user interfaces (GUI)
 
## Features
 
- A six-letter pin to login onto the maintenance page.
- Add, view, edit, and delete records.
- Finding BMI of patients.
 
## Requirements
To get along with the challenge you need to have the following:
- JAVA eclipse IDE(any version after 2018)
- ORACLE Database with the table created in it
- Custom Font (Optional,Mentioned below)
 
## NOTE
 
### Default setup
- Make sure you have JDBC installed and configured.
- The default username and password is set to 'admin'. To change password or the username, make changes in the code.
- ORACLE user and passwd is 'SAM'and 'SRI4533' respectively, You might need to change in the main code for it to work on your system.
 
## Query for creating the table:
- Execute this query in your sql command line or in your run sql command line.
```sh

CREATE TABLE  "MEDICAL_RECORDS"
   (    "ADMN_NUMBER" NUMBER NOT NULL ENABLE,
    "NAME" VARCHAR2(250),
    "AGE" NUMBER NOT NULL ENABLE,
    "GENDER" VARCHAR2(250),
    "DATE_OF_BIRTH" VARCHAR2(250),
    "HEIGHT" NUMBER,
    "WEIGHT" NUMBER,
    "BLOOD_GROUP" VARCHAR2(250),
    "COVID_STATUS" VARCHAR2(250),
    "COVID_VACCINATION_STATUS" VARCHAR2(250),
    "PAST_HISTORY" VARCHAR2(250),
    "MAJOR_ILLNESS" VARCHAR2(250),
    "IMPLANTS" VARCHAR2(250),
     CONSTRAINT "MEDICAL_RECORDS_PK" PRIMARY KEY ("ADMN_NUMBER") ENABLE
   ) ;
```


 
## Setup
- I believe you have the motivation, a computer and a dream. In addition to that basic to intermediate level knowledge in JAVA and its Modules. If you have those, then you have everything to get started.
or else i am afraid this is just too much for you my friend
 
### Download git repository
- Download ZIP and extract
  <div>OR<div>
### Clone git repository
Open git Bash.
Change the current working directory to the location where you want the cloned directory.
```sh
$ git clone https://gitlab.com/mrms/teampro/-/blob/main/MRMS_Git

```
 
#### Fonts used
- Arial
- Italic Bold
 
## You can also run the main code in eclipse idle also
 
### A Project Made By members of
- TEAMPRO
 
