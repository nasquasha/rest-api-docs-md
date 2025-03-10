# List team projects (Legacy)

`GET /teams/{team_id}/projects`

[API method documentation](https://docs.github.com/rest/teams/teams#list-team-projects-legacy)

## All Parameters for "List team projects (Legacy)"

### Path Parameters

- `team_id` (integer, required): The unique identifier of the team.
### Query Parameters

- `per_page` (integer): The number of results per page (max 100). For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)."
- `page` (integer): The page number of the results to fetch. For more information, see "[Using pagination in the REST API](https://docs.github.com/rest/using-the-rest-api/using-pagination-in-the-rest-api)."

## Operation Description

> [!WARNING]
> **Deprecation notice:** This endpoint route is deprecated and will be removed from the Teams API. We recommend migrating your existing code to use the new [`List team projects`](https://docs.github.com/rest/teams/teams#list-team-projects) endpoint.

Lists the organization projects for a team.
