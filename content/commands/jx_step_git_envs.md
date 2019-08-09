---
date: 2019-08-09T11:51:15Z
title: "jx step git envs"
slug: jx_step_git_envs
url: /commands/jx_step_git_envs/
---
## jx step git envs

Creates the Git environment variables for the current pipeline Git credentials

### Synopsis

This pipeline step generates a Git environment variables from the current Git provider pipeline Secrets

```
jx step git envs [flags]
```

### Examples

```
  # Sets the Git environment variables for the current GitHub provider
  jx step git envs
  
  # Sets the Gie environment variables for the current Gtilab provider
  jx step git envs --service-kind=gitlab
```

### Options

```
  -h, --help                  help for envs
      --service-kind string   The kind of git service (default "github")
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

* [jx step git](/commands/jx_step_git/)	 - git [command]

###### Auto generated by spf13/cobra on 9-Aug-2019