---
"@linear/sdk": major
---


feat(schema): [breaking] Field 'entityType' was removed from object type 'AiConversationNavigateToPageToolCallArgs' (AiConversationNavigateToPageToolCallArgs.entityType)

feat(schema): [breaking] Field 'identifier' was removed from object type 'AiConversationNavigateToPageToolCallArgs' (AiConversationNavigateToPageToolCallArgs.identifier)

feat(schema): [breaking] Field 'newTab' was removed from object type 'AiConversationNavigateToPageToolCallResult' (AiConversationNavigateToPageToolCallResult.newTab)

feat(schema): [breaking] Field 'url' was removed from object type 'AiConversationNavigateToPageToolCallResult' (AiConversationNavigateToPageToolCallResult.url)

feat(schema): [breaking] Input field 'ReleaseNoteCreateInput.releaseIds' changed type from '[String!]!' to '[String!]' (ReleaseNoteCreateInput.releaseIds)

feat(schema): [dangerous] Member 'AiConversationEventPart' was added to Union type 'AiConversationPart' (AiConversationPart)

feat(schema): [dangerous] Enum value 'event' was added to enum 'AiConversationPartType' (AiConversationPartType.event)

feat(schema): [dangerous] Enum value 'waiting' was added to enum 'AiConversationStatus' (AiConversationStatus.waiting)

feat(schema): [dangerous] Enum value 'GetPullRequestCheckLogs' was added to enum 'AiConversationTool' (AiConversationTool.GetPullRequestCheckLogs)

feat(schema): [dangerous] Enum value 'RetryPullRequestCheck' was added to enum 'AiConversationTool' (AiConversationTool.RetryPullRequestCheck)

feat(schema): [dangerous] Enum value 'SubscribeToEvent' was added to enum 'AiConversationTool' (AiConversationTool.SubscribeToEvent)

feat(schema): [dangerous] Enum value 'UnsubscribeFromEvent' was added to enum 'AiConversationTool' (AiConversationTool.UnsubscribeFromEvent)

feat(schema): [dangerous] Member 'AiConversationGetPullRequestCheckLogsToolCall' was added to Union type 'AiConversationToolCall' (AiConversationToolCall)

feat(schema): [dangerous] Member 'AiConversationRetryPullRequestCheckToolCall' was added to Union type 'AiConversationToolCall' (AiConversationToolCall)

feat(schema): [dangerous] Member 'AiConversationSubscribeToEventToolCall' was added to Union type 'AiConversationToolCall' (AiConversationToolCall)

feat(schema): [dangerous] Member 'AiConversationUnsubscribeFromEventToolCall' was added to Union type 'AiConversationToolCall' (AiConversationToolCall)

feat(schema): [dangerous] Input field 'rangeFromReleaseId' was added to input object type 'ReleaseNoteCreateInput' (ReleaseNoteCreateInput.rangeFromReleaseId)

feat(schema): [dangerous] Input field 'rangeToReleaseId' was added to input object type 'ReleaseNoteCreateInput' (ReleaseNoteCreateInput.rangeToReleaseId)

feat(schema): [dangerous] Input field 'rangeFromReleaseId' was added to input object type 'ReleaseNoteUpdateInput' (ReleaseNoteUpdateInput.rangeFromReleaseId)

feat(schema): [dangerous] Input field 'rangeToReleaseId' was added to input object type 'ReleaseNoteUpdateInput' (ReleaseNoteUpdateInput.rangeToReleaseId)

feat(schema): [dangerous] Input field 'pipelineId' was added to input object type 'TemplateCreateInput' (TemplateCreateInput.pipelineId)

feat(schema): [non_breaking] Type 'AiConversationEventPart' was added (AiConversationEventPart)

feat(schema): [non_breaking] Type 'AiConversationGetPullRequestCheckLogsToolCall' was added (AiConversationGetPullRequestCheckLogsToolCall)

feat(schema): [non_breaking] Type 'AiConversationGetPullRequestCheckLogsToolCallArgs' was added (AiConversationGetPullRequestCheckLogsToolCallArgs)

feat(schema): [non_breaking] Type 'AiConversationNavigateToPageToolCallArgsEntities' was added (AiConversationNavigateToPageToolCallArgsEntities)

feat(schema): [non_breaking] Type 'AiConversationRetryPullRequestCheckToolCall' was added (AiConversationRetryPullRequestCheckToolCall)

feat(schema): [non_breaking] Type 'AiConversationRetryPullRequestCheckToolCallArgs' was added (AiConversationRetryPullRequestCheckToolCallArgs)

feat(schema): [non_breaking] Type 'AiConversationSubscribeToEventToolCall' was added (AiConversationSubscribeToEventToolCall)

feat(schema): [non_breaking] Type 'AiConversationSubscribeToEventToolCallArgs' was added (AiConversationSubscribeToEventToolCallArgs)

feat(schema): [non_breaking] Type 'AiConversationSubscribeToEventToolCallArgsKind' was added (AiConversationSubscribeToEventToolCallArgsKind)

feat(schema): [non_breaking] Type 'AiConversationSubscribeToEventToolCallArgsType' was added (AiConversationSubscribeToEventToolCallArgsType)

feat(schema): [non_breaking] Type 'AiConversationUnsubscribeFromEventToolCall' was added (AiConversationUnsubscribeFromEventToolCall)

feat(schema): [non_breaking] Type 'AiConversationUnsubscribeFromEventToolCallArgs' was added (AiConversationUnsubscribeFromEventToolCallArgs)

feat(schema): [non_breaking] Field 'entities' was added to object type 'AiConversationNavigateToPageToolCallArgs' (AiConversationNavigateToPageToolCallArgs.entities)

feat(schema): [non_breaking] Field 'urls' was added to object type 'AiConversationNavigateToPageToolCallResult' (AiConversationNavigateToPageToolCallResult.urls)

feat(schema): [non_breaking] Input field 'FrontSettingsInput.automateTicketReopeningOnCancellation' description changed from 'Whether a ticket should be automatically reopened when its linked Linear issue is cancelled.' to 'Whether a ticket should be automatically reopened when its linked Linear issue is canceled.' (FrontSettingsInput.automateTicketReopeningOnCancellation)

feat(schema): [non_breaking] Input field 'FrontSettingsInput.automateTicketReopeningOnProjectCancellation' description changed from 'Whether a ticket should be automatically reopened when its linked Linear project is cancelled.' to 'Whether a ticket should be automatically reopened when its linked Linear project is canceled.' (FrontSettingsInput.automateTicketReopeningOnProjectCancellation)

feat(schema): [non_breaking] Field 'IntegrationsSettings.slackIssueStatusChangedDone' description changed from 'Whether to send a Slack message when any of the project or team's issues change to completed or cancelled.' to 'Whether to send a Slack message when any of the project or team's issues change to completed or canceled.' (IntegrationsSettings.slackIssueStatusChangedDone)

feat(schema): [non_breaking] Input field 'IntegrationsSettingsCreateInput.slackIssueStatusChangedDone' description changed from 'Whether to send a Slack message when any of the project or team's issues change to completed or cancelled.' to 'Whether to send a Slack message when any of the project or team's issues change to completed or canceled.' (IntegrationsSettingsCreateInput.slackIssueStatusChangedDone)

feat(schema): [non_breaking] Input field 'IntegrationsSettingsUpdateInput.slackIssueStatusChangedDone' description changed from 'Whether to send a Slack message when any of the project or team's issues change to completed or cancelled.' to 'Whether to send a Slack message when any of the project or team's issues change to completed or canceled.' (IntegrationsSettingsUpdateInput.slackIssueStatusChangedDone)

feat(schema): [non_breaking] Input field 'IntercomSettingsInput.automateTicketReopeningOnCancellation' description changed from 'Whether a ticket should be automatically reopened when its linked Linear issue is cancelled.' to 'Whether a ticket should be automatically reopened when its linked Linear issue is canceled.' (IntercomSettingsInput.automateTicketReopeningOnCancellation)

feat(schema): [non_breaking] Input field 'IntercomSettingsInput.automateTicketReopeningOnProjectCancellation' description changed from 'Whether a ticket should be automatically reopened when its linked Linear project is cancelled.' to 'Whether a ticket should be automatically reopened when its linked Linear project is canceled.' (IntercomSettingsInput.automateTicketReopeningOnProjectCancellation)

feat(schema): [non_breaking] Input field 'ReleaseNoteCreateInput.releaseIds' description changed from 'The releases included in this note.' to 'Explicit release IDs to include. Mutually exclusive with rangeFromReleaseId/rangeToReleaseId — exactly one of the two shapes must be provided.' (ReleaseNoteCreateInput.releaseIds)

feat(schema): [non_breaking] Input field 'ReleaseNoteUpdateInput.releaseIds' description changed from 'The releases included in this note.' to 'Explicit release IDs to set. Mutually exclusive with rangeFromReleaseId/rangeToReleaseId.' (ReleaseNoteUpdateInput.releaseIds)

feat(schema): [non_breaking] Field 'releaseNoteTemplate' was added to object type 'ReleasePipeline' (ReleasePipeline.releaseNoteTemplate)

feat(schema): [non_breaking] Input field 'SalesforceSettingsInput.automateTicketReopeningOnCancellation' description changed from 'Whether a ticket should be automatically reopened when its linked Linear issue is cancelled.' to 'Whether a ticket should be automatically reopened when its linked Linear issue is canceled.' (SalesforceSettingsInput.automateTicketReopeningOnCancellation)

feat(schema): [non_breaking] Input field 'SalesforceSettingsInput.automateTicketReopeningOnProjectCancellation' description changed from 'Whether a ticket should be automatically reopened when its linked Linear project is cancelled.' to 'Whether a ticket should be automatically reopened when its linked Linear project is canceled.' (SalesforceSettingsInput.automateTicketReopeningOnProjectCancellation)

feat(schema): [non_breaking] Field 'pipeline' was added to object type 'Template' (Template.pipeline)

feat(schema): [non_breaking] Field 'groupOrderingMode' was added to object type 'ViewPreferencesValues' (ViewPreferencesValues.groupOrderingMode)

feat(schema): [non_breaking] Field 'ViewPreferencesValues.projectGroupOrdering' is deprecated (ViewPreferencesValues.projectGroupOrdering)

feat(schema): [non_breaking] Field 'ViewPreferencesValues.projectGroupOrdering' has deprecation reason 'Use groupOrderingMode instead.' (ViewPreferencesValues.projectGroupOrdering)

feat(schema): [non_breaking] Input field 'ZendeskSettingsInput.automateTicketReopeningOnCancellation' description changed from 'Whether a ticket should be automatically reopened when its linked Linear issue is cancelled.' to 'Whether a ticket should be automatically reopened when its linked Linear issue is canceled.' (ZendeskSettingsInput.automateTicketReopeningOnCancellation)

feat(schema): [non_breaking] Input field 'ZendeskSettingsInput.automateTicketReopeningOnProjectCancellation' description changed from 'Whether a ticket should be automatically reopened when its linked Linear project is cancelled.' to 'Whether a ticket should be automatically reopened when its linked Linear project is canceled.' (ZendeskSettingsInput.automateTicketReopeningOnProjectCancellation)