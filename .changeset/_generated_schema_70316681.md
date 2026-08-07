---
"@linear/sdk": major
---


feat(schema): [breaking] Input field 'InitiativeCollectionFilter.id' changed type from 'IDComparator' to 'EntityIdentifierIDComparator' (InitiativeCollectionFilter.id)

feat(schema): [breaking] Input field 'InitiativeFilter.id' changed type from 'IDComparator' to 'EntityIdentifierIDComparator' (InitiativeFilter.id)

feat(schema): [breaking] Input field 'NullableInitiativeFilter.id' changed type from 'IDComparator' to 'EntityIdentifierIDComparator' (NullableInitiativeFilter.id)

feat(schema): [breaking] Input field 'NullableProjectFilter.id' changed type from 'IDComparator' to 'EntityIdentifierIDComparator' (NullableProjectFilter.id)

feat(schema): [breaking] Input field 'ProjectCollectionFilter.id' changed type from 'IDComparator' to 'EntityIdentifierIDComparator' (ProjectCollectionFilter.id)

feat(schema): [breaking] Input field 'ProjectFilter.id' changed type from 'IDComparator' to 'EntityIdentifierIDComparator' (ProjectFilter.id)

feat(schema): [dangerous] Enum value 'featureDisabled' was added to enum 'AiConversationErrorType' (AiConversationErrorType.featureDisabled)

feat(schema): [dangerous] Enum value 'usageLimit' was added to enum 'AiConversationErrorType' (AiConversationErrorType.usageLimit)

feat(schema): [dangerous] Input field 'customIdentifier' was added to input object type 'InitiativeCollectionFilter' (InitiativeCollectionFilter.customIdentifier)

feat(schema): [dangerous] Input field 'customIdentifier' was added to input object type 'InitiativeFilter' (InitiativeFilter.customIdentifier)

feat(schema): [dangerous] Argument 'customApiUrl: String' added to field 'Mutation.integrationZendesk' (Mutation.integrationZendesk.customApiUrl)

feat(schema): [dangerous] Input field 'customIdentifier' was added to input object type 'NullableInitiativeFilter' (NullableInitiativeFilter.customIdentifier)

feat(schema): [dangerous] Input field 'customIdentifier' was added to input object type 'NullableProjectFilter' (NullableProjectFilter.customIdentifier)

feat(schema): [dangerous] Input field 'customIdentifier' was added to input object type 'ProjectCollectionFilter' (ProjectCollectionFilter.customIdentifier)

feat(schema): [dangerous] Input field 'customIdentifier' was added to input object type 'ProjectFilter' (ProjectFilter.customIdentifier)

feat(schema): [dangerous] Input field 'customApiUrl' was added to input object type 'ZendeskSettingsInput' (ZendeskSettingsInput.customApiUrl)

feat(schema): [non_breaking] Type 'AgentAutomationUsageLimitScope' was added (AgentAutomationUsageLimitScope)

feat(schema): [non_breaking] Type 'EntityIdentifierIDComparator' was added (EntityIdentifierIDComparator)

feat(schema): [non_breaking] Field 'usageLimitResetsAt' was added to object type 'AiConversationErrorPart' (AiConversationErrorPart.usageLimitResetsAt)

feat(schema): [non_breaking] Field 'usageLimitScope' was added to object type 'AiConversationErrorPart' (AiConversationErrorPart.usageLimitScope)

feat(schema): [non_breaking] Field 'aiConversationId' was added to object type 'WorkflowDefinitionNotification' (WorkflowDefinitionNotification.aiConversationId)

feat(schema): [non_breaking] Input field 'ZendeskSettingsInput.url' description changed from 'The URL of the connected Zendesk organization.' to 'The URL of the connected Zendesk organization, used to link into Zendesk. API requests use `customApiUrl` when it is set.' (ZendeskSettingsInput.url)