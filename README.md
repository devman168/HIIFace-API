![](https://img.shields.io/badge/-HIIFace%20API-success) 
![](https://img.shields.io/badge/-%20V%202.0-blue)

# HIIFace-API

Version 2.0.0

###### Host-IP = Public IP / Domain Name , Example face.hii.xyz 

#### 1. Recognition

Path : Host-IP/api/recognition

Method : POST 

Interface Description : Recognition.

##### Request parameter : 

| Name      | Type |
| --------- | -----|
| key  |text|
| photo     |file|

##### Return data :

| Name      | Type |
| --------- | -----|
| status|-|
| id_no|-|
| firstname|-|
| lastname|-|
| emid|-|
| photo|-|
| distance|-|

---

#### 2. Register

Path : Host-IP/api/register

Method : POST 

Interface Description : Register.

##### Request parameter : 

| Name      | Type |
| --------- | -----|
| key|text|
| id_no|number|
| emid|text|
| firstname|text|
| lastname|text|
| photo|file|

##### Return data :

| Name      | Type |
| --------- | -----|
| status|-|
| message|-|

---

#### 3. Update

Path : Host-IP/api/update

Method : PUT

Interface Description : Update.

##### Request parameter : 

| Name      | Type |
| --------- | -----|
| key|text|
| id_no|number|
| emid|text|
| firstname|text|
| lastname|text|
| photo|file|

##### Return data :

| Name      | Type |
| --------- | -----|
| status|-|
| message|-|

---

#### 4. Remove

Path : Host-IP/api/remove

Method : DELETE

Interface Description : Delete.

##### Request parameter : 

| Name      | Type |
| --------- | -----|
| key  |text|
| id_no|number|

##### Return data :

| Name      | Type |
| --------- | -----|
| status|-|
| message|-|

---
