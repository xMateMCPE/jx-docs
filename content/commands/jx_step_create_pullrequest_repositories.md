---
date: 2019-07-01T09:40:44Z
title: "jx step create pullrequest repositories"
slug: jx_step_create_pullrequest_repositories
url: /commands/jx_step_create_pullrequest_repositories/
---
## jx step create pullrequest repositories

Creates a Pull Request on a 'jx boot' git repository to mirror all the SourceRepository CRDs into the repositories Chart

### Synopsis

Creates a Pull Request on a 'jx boot' git repository to mirror all the SourceRepository CRDs into the repositories Chart

```
jx step create pullrequest repositories [flags]
```

### Examples

```
  
```

### Options

```
      --base string        The branch to create the pull request into (default "master")
      --branch string      Branch to clone and generate a pull request from (default "master")
      --component string   The component of the git repo which caused this change; useful if you have a complex or monorepo setup and want to differentiate between different components from the same repo
  -h, --help               help for repositories
  -r, --repo string        Git repo
      --srcRepo string     The git repo which caused this change; if this is a dependency update this will cause commit messages to be generated which can be parsed by jx step changelog. By default this will be read from the environment variable REPO_URL
  -v, --version string     The version to change. If no version is supplied the latest version is found
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --config-file string        Configuration file used for installation
      --install-dependencies      Enables automatic dependencies installation when required
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx step create pullrequest](/commands/jx_step_create_pullrequest/)	 - create pullrequest [command]

###### Auto generated by spf13/cobra on 1-Jul-2019