# List labels for a self-hosted runner for a repository

`GET /repos/{owner}/{repo}/actions/runners/{runner_id}/labels`

[API method documentation](https://docs.github.com/rest/actions/self-hosted-runners#list-labels-for-a-self-hosted-runner-for-a-repository)

## All Parameters for "List labels for a self-hosted runner for a repository"

### Path Parameters

- `owner` (string, required): The account owner of the repository. The name is not case sensitive.
- `repo` (string, required): The name of the repository without the `.git` extension. The name is not case sensitive.
- `runner_id` (integer, required): Unique identifier of the self-hosted runner.

## Operation Description

Lists all labels for a self-hosted runner configured in a repository.

Authenticated users must have admin access to the repository to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.
