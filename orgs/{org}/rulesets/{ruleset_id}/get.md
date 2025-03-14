# Get an organization repository ruleset

`GET /orgs/{org}/rulesets/{ruleset_id}`

[API method documentation](https://docs.github.com/rest/orgs/rules#get-an-organization-repository-ruleset)

## All Parameters for "Get an organization repository ruleset"

### Path Parameters

- `org` (string, required): The organization name. The name is not case sensitive.
- `ruleset_id` (integer, required): The ID of the ruleset.

## Operation Description

Get a repository ruleset for an organization.

**Note:** To prevent leaking sensitive information, the `bypass_actors` property is only returned if the user
making the API request has write access to the ruleset.
