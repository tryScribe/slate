--- 

title: API 

language_tabs: 
   - shell 

toc_footers: 
   - <a href='#'>Sign Up for a Developer Key</a> 
   - <a href='https://github.com/lavkumarv'>Documentation Powered by lav</a> 

includes: 
   - errors 

search: true 

--- 

# Introduction 

**Version:** 1.0 

# Authentication 

|apiKey|*API Key*|
|---|---| 

# /LEADS
## ***POST*** 

**Summary:** Add new lead

**Description:** :return:
:rtype:

### HTTP Request 
`***POST*** /leads` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

## ***GET*** 

**Summary:** get Lead List

**Description:** :return:
:rtype:

### HTTP Request 
`***GET*** /leads` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /LEADS/{LEADID}
## ***DELETE*** 

### HTTP Request 
`***DELETE*** /leads/{leadId}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| leadId | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

## ***GET*** 

### HTTP Request 
`***GET*** /leads/{leadId}` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| leadId | path |  | Yes | integer |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /QUALIFY
## ***GET*** 

### HTTP Request 
`***GET*** /qualify` 

**Parameters**

| Name | Located in | Description | Required | Type |
| ---- | ---------- | ----------- | -------- | ---- |
| company | query | company of the associated lead | No | string |
| email | query | email of lead to qualify | No | string |

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

# /SALESREPS
## ***GET*** 

### HTTP Request 
`***GET*** /salesReps` 

**Responses**

| Code | Description |
| ---- | ----------- |
| 200 | Success |

<!-- Converted with the swagger-to-slate https://github.com/lavkumarv/swagger-to-slate -->
