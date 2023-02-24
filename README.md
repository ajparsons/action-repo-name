# Extract repo name

Version: 1.0.0

Extract repo name from user/repo

## Usage

```yaml

# It is better practice to use the SHA hash of this tag rather than the tag itself.
- uses: ajparsons/action-repo-name@v1
  id: example-step 
  with:
    github_repo: '' 

```

## Inputs

### github_repo

Required.

Github repo user/repo combination.

## Outputs

### repo_name

The repo of 'user/repo'.

