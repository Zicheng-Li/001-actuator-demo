# 001-actuator-demo
Actuator
---
how: `starter-actuator`					

`/health`
`/info`
`/beans`
`/mappings`
`/threaddump`
`/auditevents`

--
common properties:
`core web security`  
log levels: `TRACE INFO DEBUG`  
context path of the app: `servlet.context-path=/my-silly-app/hello`  
Actuator: `exclude=beans,mapping` and `include=*`  
Security: `.user.name=admin` and `.user.password=8888`  
