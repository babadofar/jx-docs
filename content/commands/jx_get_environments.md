---
date: 2019-08-09T11:51:15Z
title: "jx get environments"
slug: jx_get_environments
url: /commands/jx_get_environments/
---
## jx get environments

Display one or more Environments

### Synopsis

Display one or more environments.
  
See Also: 

  * jx get previews : https://jenkins-x.io/commands/jx_get_previews

```
jx get environments [flags]
```

### Examples

```
  # List all environments
  jx get environments
  
  # List all environments using the shorter alias
  jx get env
```

### Options

```
  -h, --help             help for environments
  -o, --output string    The output format such as 'yaml'
  -p, --promote string   Filters the environments by promotion strategy. Possible values: Auto, Manual, Never
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

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 9-Aug-2019