---
date: 2019-08-09T11:51:15Z
title: "jx update"
slug: jx_update
url: /commands/jx_update/
---
## jx update

Updates an existing resource

### Synopsis

Updates an existing resource.
  
  Valid resource types include:
  
  * cluster

```
jx update [flags]
```

### Options

```
  -h, --help   help for update
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

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X
* [jx update cluster](/commands/jx_update_cluster/)	 - Updates an existing Kubernetes cluster
* [jx update webhooks](/commands/jx_update_webhooks/)	 - Updates the webhooks for all the source repositories optionally filtering by owner and/or repository

###### Auto generated by spf13/cobra on 9-Aug-2019