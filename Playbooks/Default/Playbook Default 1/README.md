# Playbook Default 1




**Enabled:** True

**Version:** 1

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Siemplify_Case Comment_1|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Change Priority_1|Automatically change case priority to the given input|Siemplify|Change Priority|
|Siemplify_Get Similar Cases_1|Search for similar cases and return their Ids|Siemplify|Get Similar Cases|
|Siemplify_Create Entity_1|Creates an entity and adds to requested alert. Note - Please make sure to read our documentation regarding the differences in the delimiter’s behavior, between different Siemplify’s platform versions 5.6.0 inclusive and 5.6.2 exclusive, here: https://cloud.google.com/chronicle/docs/soar/marketplace-integrations/siemplify#create-entity|Siemplify|Create Entity|

