# Some-Imp-SOQL
/* get List of flows  */
SELECT Id, ApiName, TriggerType, Label, IsActive FROM FlowDefinitionView 

/* List of all object in salesforce org */
SELECT QualifiedApiName, Label, ExternalSharingModel, InternalSharingModel, DurableId, DeploymentStatus, NamespacePrefix, LastModifiedDate, LastModifiedById FROM EntityDefinition ORDER BY QualifiedApiName 
