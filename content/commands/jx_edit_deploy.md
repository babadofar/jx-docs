---
date: 2019-08-09T11:51:15Z
title: "jx edit deploy"
slug: jx_edit_deploy
url: /commands/jx_edit_deploy/
---
## jx edit deploy

Edits the deploy kind to use for your project or team

### Synopsis

Edits the deploy kind to use for your project or team

```
jx edit deploy [flags]
```

### Examples

```
  # Edit the deploy kind for your current project and prompts you to pick one of the available kinds
  jx edit deploy
  
  # to switch to use Knative Serve deployments
  jx edit deploy knative
  
  # to switch to normal kubernetes deployments
  jx edit deploy default
  
  # Edit the default deploy kind for your team
  jx edit deploy --team
  
  # Set the default for your team to use knative
  jx edit deploy --team knative
```

### Options

```
  -h, --help          help for deploy
  -k, --kind string   The kind to use which should be one of: knative, default
  -t, --team          Edits the team default
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

* [jx edit](/commands/jx_edit/)	 - Edit a resource

###### Auto generated by spf13/cobra on 9-Aug-2019