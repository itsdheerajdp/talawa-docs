[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / Mutation

# Type Alias: Mutation

> **Mutation**: `object`

## Type declaration

### \_\_typename?

> `optional` **\_\_typename**: `"Mutation"`

### acceptMembershipRequest

> **acceptMembershipRequest**: [`MembershipRequest`](MembershipRequest.md)

### addEventAttendee

> **addEventAttendee**: [`User`](User.md)

### addFeedback

> **addFeedback**: [`Feedback`](Feedback.md)

### addLanguageTranslation

> **addLanguageTranslation**: [`Language`](Language.md)

### addOrganizationCustomField

> **addOrganizationCustomField**: [`OrganizationCustomField`](OrganizationCustomField.md)

### addOrganizationImage

> **addOrganizationImage**: [`Organization`](Organization.md)

### addPledgeToFundraisingCampaign

> **addPledgeToFundraisingCampaign**: [`FundraisingCampaignPledge`](FundraisingCampaignPledge.md)

### addUserCustomData

> **addUserCustomData**: [`UserCustomData`](UserCustomData.md)

### addUserImage

> **addUserImage**: [`User`](User.md)

### addUserToGroupChat

> **addUserToGroupChat**: [`GroupChat`](GroupChat.md)

### addUserToUserFamily

> **addUserToUserFamily**: [`UserFamily`](UserFamily.md)

### adminRemoveGroup

> **adminRemoveGroup**: [`GroupChat`](GroupChat.md)

### assignUserTag?

> `optional` **assignUserTag**: [`Maybe`](Maybe.md)\<[`User`](User.md)\>

### blockPluginCreationBySuperadmin

> **blockPluginCreationBySuperadmin**: [`AppUserProfile`](AppUserProfile.md)

### blockUser

> **blockUser**: [`User`](User.md)

### cancelMembershipRequest

> **cancelMembershipRequest**: [`MembershipRequest`](MembershipRequest.md)

### checkIn

> **checkIn**: [`CheckIn`](CheckIn.md)

### checkOut

> **checkOut**: [`CheckOut`](CheckOut.md)

### createActionItem

> **createActionItem**: [`ActionItem`](ActionItem.md)

### createActionItemCategory

> **createActionItemCategory**: [`ActionItemCategory`](ActionItemCategory.md)

### createAdmin

> **createAdmin**: [`CreateAdminPayload`](CreateAdminPayload.md)

### createAdvertisement?

> `optional` **createAdvertisement**: [`Maybe`](Maybe.md)\<[`CreateAdvertisementPayload`](CreateAdvertisementPayload.md)\>

### createAgendaCategory

> **createAgendaCategory**: [`AgendaCategory`](AgendaCategory.md)

### createAgendaItem

> **createAgendaItem**: [`AgendaItem`](AgendaItem.md)

### createAgendaSection

> **createAgendaSection**: [`AgendaSection`](AgendaSection.md)

### createComment?

> `optional` **createComment**: [`Maybe`](Maybe.md)\<[`Comment`](Comment.md)\>

### createDirectChat

> **createDirectChat**: [`DirectChat`](DirectChat.md)

### createDonation

> **createDonation**: [`Donation`](Donation.md)

### createEvent

> **createEvent**: [`Event`](Event.md)

### createEventVolunteer

> **createEventVolunteer**: [`EventVolunteer`](EventVolunteer.md)

### createEventVolunteerGroup

> **createEventVolunteerGroup**: [`EventVolunteerGroup`](EventVolunteerGroup.md)

### createFund

> **createFund**: [`Fund`](Fund.md)

### createFundraisingCampaign

> **createFundraisingCampaign**: [`FundraisingCampaign`](FundraisingCampaign.md)

### createFundraisingCampaignPledge

> **createFundraisingCampaignPledge**: [`FundraisingCampaignPledge`](FundraisingCampaignPledge.md)

### createGroupChat

> **createGroupChat**: [`GroupChat`](GroupChat.md)

### createMember

> **createMember**: [`CreateMemberPayload`](CreateMemberPayload.md)

### createMessageChat

> **createMessageChat**: [`MessageChat`](MessageChat.md)

### createNote

> **createNote**: [`Note`](Note.md)

### createOrganization

> **createOrganization**: [`Organization`](Organization.md)

### createPlugin

> **createPlugin**: [`Plugin`](Plugin.md)

### createPost?

> `optional` **createPost**: [`Maybe`](Maybe.md)\<[`Post`](Post.md)\>

### createSampleOrganization

> **createSampleOrganization**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### createUserFamily

> **createUserFamily**: [`UserFamily`](UserFamily.md)

### createUserTag?

> `optional` **createUserTag**: [`Maybe`](Maybe.md)\<[`UserTag`](UserTag.md)\>

### createVenue?

> `optional` **createVenue**: [`Maybe`](Maybe.md)\<[`Venue`](Venue.md)\>

### deleteAdvertisement?

> `optional` **deleteAdvertisement**: [`Maybe`](Maybe.md)\<[`DeleteAdvertisementPayload`](DeleteAdvertisementPayload.md)\>

### deleteAgendaCategory

> **deleteAgendaCategory**: [`Scalars`](Scalars.md)\[`"ID"`\]\[`"output"`\]

### deleteDonationById

> **deleteDonationById**: [`DeletePayload`](DeletePayload.md)

### deleteNote

> **deleteNote**: [`Scalars`](Scalars.md)\[`"ID"`\]\[`"output"`\]

### deleteVenue?

> `optional` **deleteVenue**: [`Maybe`](Maybe.md)\<[`Venue`](Venue.md)\>

### editVenue?

> `optional` **editVenue**: [`Maybe`](Maybe.md)\<[`Venue`](Venue.md)\>

### forgotPassword

> **forgotPassword**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### inviteEventAttendee

> **inviteEventAttendee**: [`EventAttendee`](EventAttendee.md)

### joinPublicOrganization

> **joinPublicOrganization**: [`User`](User.md)

### leaveOrganization

> **leaveOrganization**: [`User`](User.md)

### likeComment?

> `optional` **likeComment**: [`Maybe`](Maybe.md)\<[`Comment`](Comment.md)\>

### likePost?

> `optional` **likePost**: [`Maybe`](Maybe.md)\<[`Post`](Post.md)\>

### login

> **login**: [`AuthData`](AuthData.md)

### logout

> **logout**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### otp

> **otp**: [`OtpData`](OtpData.md)

### recaptcha

> **recaptcha**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### refreshToken

> **refreshToken**: [`ExtendSession`](ExtendSession.md)

### registerEventAttendee

> **registerEventAttendee**: [`EventAttendee`](EventAttendee.md)

### registerForEvent

> **registerForEvent**: [`EventAttendee`](EventAttendee.md)

### rejectMembershipRequest

> **rejectMembershipRequest**: [`MembershipRequest`](MembershipRequest.md)

### removeActionItem

> **removeActionItem**: [`ActionItem`](ActionItem.md)

### removeAdmin

> **removeAdmin**: [`AppUserProfile`](AppUserProfile.md)

### removeAdvertisement?

> `optional` **removeAdvertisement**: [`Maybe`](Maybe.md)\<[`Advertisement`](Advertisement.md)\>

### removeAgendaItem

> **removeAgendaItem**: [`AgendaItem`](AgendaItem.md)

### removeAgendaSection

> **removeAgendaSection**: [`Scalars`](Scalars.md)\[`"ID"`\]\[`"output"`\]

### removeComment?

> `optional` **removeComment**: [`Maybe`](Maybe.md)\<[`Comment`](Comment.md)\>

### removeDirectChat

> **removeDirectChat**: [`DirectChat`](DirectChat.md)

### removeEvent

> **removeEvent**: [`Event`](Event.md)

### removeEventAttendee

> **removeEventAttendee**: [`User`](User.md)

### removeEventVolunteer

> **removeEventVolunteer**: [`EventVolunteer`](EventVolunteer.md)

### removeEventVolunteerGroup

> **removeEventVolunteerGroup**: [`EventVolunteerGroup`](EventVolunteerGroup.md)

### removeFund

> **removeFund**: [`Fund`](Fund.md)

### removeFundraisingCampaign

> **removeFundraisingCampaign**: [`FundraisingCampaign`](FundraisingCampaign.md)

### removeFundraisingCampaignPledge

> **removeFundraisingCampaignPledge**: [`FundraisingCampaignPledge`](FundraisingCampaignPledge.md)

### removeGroupChat

> **removeGroupChat**: [`GroupChat`](GroupChat.md)

### removeMember

> **removeMember**: [`Organization`](Organization.md)

### removeOrganization

> **removeOrganization**: [`UserData`](UserData.md)

### removeOrganizationCustomField

> **removeOrganizationCustomField**: [`OrganizationCustomField`](OrganizationCustomField.md)

### removeOrganizationImage

> **removeOrganizationImage**: [`Organization`](Organization.md)

### removePost?

> `optional` **removePost**: [`Maybe`](Maybe.md)\<[`Post`](Post.md)\>

### removeSampleOrganization

> **removeSampleOrganization**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### removeUserCustomData

> **removeUserCustomData**: [`UserCustomData`](UserCustomData.md)

### removeUserFamily

> **removeUserFamily**: [`UserFamily`](UserFamily.md)

### removeUserFromGroupChat

> **removeUserFromGroupChat**: [`GroupChat`](GroupChat.md)

### removeUserFromUserFamily

> **removeUserFromUserFamily**: [`UserFamily`](UserFamily.md)

### removeUserImage

> **removeUserImage**: [`User`](User.md)

### removeUserTag?

> `optional` **removeUserTag**: [`Maybe`](Maybe.md)\<[`UserTag`](UserTag.md)\>

### resetCommunity

> **resetCommunity**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### revokeRefreshTokenForUser

> **revokeRefreshTokenForUser**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### saveFcmToken

> **saveFcmToken**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### sendMembershipRequest

> **sendMembershipRequest**: [`MembershipRequest`](MembershipRequest.md)

### sendMessageToDirectChat

> **sendMessageToDirectChat**: [`DirectChatMessage`](DirectChatMessage.md)

### sendMessageToGroupChat

> **sendMessageToGroupChat**: [`GroupChatMessage`](GroupChatMessage.md)

### signUp

> **signUp**: [`AuthData`](AuthData.md)

### togglePostPin

> **togglePostPin**: [`Post`](Post.md)

### unassignUserTag?

> `optional` **unassignUserTag**: [`Maybe`](Maybe.md)\<[`User`](User.md)\>

### unblockUser

> **unblockUser**: [`User`](User.md)

### unlikeComment?

> `optional` **unlikeComment**: [`Maybe`](Maybe.md)\<[`Comment`](Comment.md)\>

### unlikePost?

> `optional` **unlikePost**: [`Maybe`](Maybe.md)\<[`Post`](Post.md)\>

### unregisterForEventByUser

> **unregisterForEventByUser**: [`Event`](Event.md)

### updateActionItem?

> `optional` **updateActionItem**: [`Maybe`](Maybe.md)\<[`ActionItem`](ActionItem.md)\>

### updateActionItemCategory?

> `optional` **updateActionItemCategory**: [`Maybe`](Maybe.md)\<[`ActionItemCategory`](ActionItemCategory.md)\>

### updateAdvertisement?

> `optional` **updateAdvertisement**: [`Maybe`](Maybe.md)\<[`UpdateAdvertisementPayload`](UpdateAdvertisementPayload.md)\>

### updateAgendaCategory?

> `optional` **updateAgendaCategory**: [`Maybe`](Maybe.md)\<[`AgendaCategory`](AgendaCategory.md)\>

### updateAgendaItem?

> `optional` **updateAgendaItem**: [`Maybe`](Maybe.md)\<[`AgendaItem`](AgendaItem.md)\>

### updateAgendaSection?

> `optional` **updateAgendaSection**: [`Maybe`](Maybe.md)\<[`AgendaSection`](AgendaSection.md)\>

### updateCommunity

> **updateCommunity**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### updateEvent

> **updateEvent**: [`Event`](Event.md)

### updateEventVolunteer

> **updateEventVolunteer**: [`EventVolunteer`](EventVolunteer.md)

### updateEventVolunteerGroup

> **updateEventVolunteerGroup**: [`EventVolunteerGroup`](EventVolunteerGroup.md)

### updateFund

> **updateFund**: [`Fund`](Fund.md)

### updateFundraisingCampaign

> **updateFundraisingCampaign**: [`FundraisingCampaign`](FundraisingCampaign.md)

### updateFundraisingCampaignPledge

> **updateFundraisingCampaignPledge**: [`FundraisingCampaignPledge`](FundraisingCampaignPledge.md)

### updateLanguage

> **updateLanguage**: [`User`](User.md)

### updateNote

> **updateNote**: [`Note`](Note.md)

### updateOrganization

> **updateOrganization**: [`Organization`](Organization.md)

### updatePluginStatus

> **updatePluginStatus**: [`Plugin`](Plugin.md)

### updatePost

> **updatePost**: [`Post`](Post.md)

### updateUserPassword

> **updateUserPassword**: [`UserData`](UserData.md)

### updateUserProfile

> **updateUserProfile**: [`User`](User.md)

### updateUserRoleInOrganization

> **updateUserRoleInOrganization**: [`Organization`](Organization.md)

### updateUserTag?

> `optional` **updateUserTag**: [`Maybe`](Maybe.md)\<[`UserTag`](UserTag.md)\>

## Defined in

[src/types/generatedGraphQLTypes.ts:1147](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/types/generatedGraphQLTypes.ts#L1147)
