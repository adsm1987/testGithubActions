# testGithubActions
### Running

In this case the only thing that we need to run our project in the pipeline and run tests is just do a commit to the repository or a PR that is currently specified here.

```yaml
on:
  # Triggers the workflow on push or pull request events but only for the "main" branch
  push:
    branches: [ "main" ]
  pull_request:
    branches: [ "main" ]
```

### Pipeline code 

`.github/workflows/main.yml`

