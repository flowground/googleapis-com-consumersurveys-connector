# ![LOGO](logo.png) Consumer Surveys **flow**ground Connector

## Description

A generated **flow**ground connector for the Consumer Surveys API (version v2).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/consumersurveys/v2/swagger.json<br/>
Generated at: 2019-05-07T17:41:27+03:00

## API Description

Creates and conducts surveys, lists the surveys that an authenticated user owns, and retrieves survey results and information about specified surveys.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists the MobileAppPanels available to the authenticated user.

*Tags:* `mobileapppanels`

#### Input Parameters
* `maxResults` - _optional_
* `startIndex` - _optional_
* `token` - _optional_
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Retrieves a MobileAppPanel that is available to the authenticated user.

*Tags:* `mobileapppanels`

#### Input Parameters
* `panelId` - _required_ - External URL ID for the panel.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Updates a MobileAppPanel. Currently the only property that can be updated is the owners property.

*Tags:* `mobileapppanels`

#### Input Parameters
* `panelId` - _required_ - External URL ID for the panel.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Lists the surveys owned by the authenticated user.

*Tags:* `surveys`

#### Input Parameters
* `maxResults` - _optional_
* `startIndex` - _optional_
* `token` - _optional_
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Creates a survey.

*Tags:* `surveys`

#### Input Parameters
* `alt` - _optional_ - Data format for the response.
    Possible values: json.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Begins running a survey.

*Tags:* `surveys`

#### Input Parameters
* `resourceId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Stops a running survey.

*Tags:* `surveys`

#### Input Parameters
* `resourceId` - _required_
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Removes a survey from view in all user GET requests.

*Tags:* `surveys`

#### Input Parameters
* `surveyUrlId` - _required_ - External URL ID for the survey.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Retrieves information about the specified survey.

*Tags:* `surveys`

#### Input Parameters
* `surveyUrlId` - _required_ - External URL ID for the survey.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Updates a survey. Currently the only property that can be updated is the owners property.

*Tags:* `surveys`

#### Input Parameters
* `surveyUrlId` - _required_ - External URL ID for the survey.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

### Retrieves any survey results that have been produced so far. Results are formatted as an Excel file. You must add "?alt=media" to the URL as an argument to get results.

*Tags:* `results`

#### Input Parameters
* `surveyUrlId` - _required_ - External URL ID for the survey.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters. Overrides userIp if both are provided.
* `userIp` - _optional_ - IP address of the site where the request originates. Use this if you want to enforce per-user limits.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-consumersurveys-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
