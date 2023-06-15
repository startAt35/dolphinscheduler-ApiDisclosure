# Introduction

Apache DolphinScheduler is a distributed and easily extensible open source system for visual DAG workflow task scheduling. Applicable to enterprise-level scenarios, it provides a solution for visualizing operational tasks, workflows, and data processing processes throughout the life cycle.

**Reproduce the environment**

DolphinScheduler version:3.1.7

OS:Linux/Ubuntu

# Vulnerability details
Access vulnerability address:`/dolphinscheduler/swagger-ui/index.html?language=zh_CN&lang=cn`,
you can access swagger api pages without authorization
![](pic/Pasted%20image%2020230615221036.png)
![](pic/Pasted%20image%2020230615222306.png)
Visit the following address:`http://45.77.173.91:12345/dolphinscheduler/v3/api-docs?group=v1(current)`,you can also view all interface information
![](pic/Pasted%20image%2020230615221358.png)







