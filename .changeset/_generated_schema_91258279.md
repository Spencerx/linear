---
"@linear/sdk": minor
---


feat(schema): [dangerous] Input field 'aiConversationId' was added to input object type 'FavoriteCreateInput' (FavoriteCreateInput.aiConversationId)

feat(schema): [non_breaking] Type 'PartnerApplicationCreateInput' was added (PartnerApplicationCreateInput)

feat(schema): [non_breaking] Field 'pullRequest' was added to object type 'AiConversation' (AiConversation.pullRequest)

feat(schema): [non_breaking] Field 'AiConversation.readAt' description changed from 'The time when the user marked the conversation as read. Null if the user hasn't read the conversation.' to 'The time when the current user marked the conversation as read. Null if the user hasn't read the conversation.' (AiConversation.readAt)

feat(schema): [non_breaking] Field 'aiConversation' was added to object type 'Favorite' (Favorite.aiConversation)

feat(schema): [non_breaking] Description 'A user's bookmarked item that appears in their sidebar for quick access. Favorites can reference various entity types including issues, projects, cycles, views, documents, initiatives, labels, users, customers, dashboards, and pull requests. Favorites can be organized into folders and ordered by the user. Each favorite is owned by a single user and links to exactly one target entity (or is a folder containing other favorites).' on type 'Favorite' has changed to 'A user's bookmarked item that appears in their sidebar for quick access. Favorites can reference various entity types including issues, projects, cycles, views, documents, initiatives, labels, users, customers, dashboards, pull requests, and Agent conversations. Favorites can be organized into folders and ordered by the user. Each favorite is owned by a single user and links to exactly one target entity (or is a folder containing other favorites).' (Favorite)

feat(schema): [non_breaking] Field 'ssoVerifiedAt' was added to object type 'IdentityProvider' (IdentityProvider.ssoVerifiedAt)

feat(schema): [non_breaking] Field 'partnerApplicationCreate' was added to object type 'Mutation' (Mutation.partnerApplicationCreate)

feat(schema): [non_breaking] Field 'autoMergeEnabled' was added to object type 'PullRequest' (PullRequest.autoMergeEnabled)

feat(schema): [non_breaking] Field 'PullRequestCommit.additions' description changed from 'Number of additions in this commit.' to 'Number of additions in this commit. 0 when the hosting provider did not report per-commit diff stats.' (PullRequestCommit.additions)

feat(schema): [non_breaking] Field 'PullRequestCommit.deletions' description changed from 'Number of deletions in this commit.' to 'Number of deletions in this commit. 0 when the hosting provider did not report per-commit diff stats.' (PullRequestCommit.deletions)