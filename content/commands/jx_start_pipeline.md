---
date: 2019-08-09T11:51:15Z
title: "jx start pipeline"
slug: jx_start_pipeline
url: /commands/jx_start_pipeline/
---
## jx start pipeline

Starts one or more pipelines

### Synopsis

Starts the pipeline build.

```
jx start pipeline [flags]
```

### Examples

```
  # Start a pipeline
  jx start pipeline foo
  
  # Select the pipeline to start
  jx start pipeline
  
  # Select the pipeline to start and tail the log
  jx start pipeline -t
```

### Options

```
  -c, --context string           An optional Prow pipeline context
  -m, --custom                   Use a custom Jenkins App instead of the default execution engine in Jenkins X
  -e, --env stringArray          List of custom environment variables to be applied to the generated PipelineRun that are created (can be use multiple times)
  -f, --filter string            Filters all the available jobs by those that contain the given text
  -h, --help                     help for pipeline
  -j, --jenkins-name string      The name of the custom Jenkins App if you don't wish to use the default execution engine in Jenkins X
  -l, --label stringArray        List of custom labels to be applied to the generated PipelineRun (can be use multiple times)
      --service-account string   The Kubernetes ServiceAccount to use to run the meta pipeline (default "tekton-bot")
  -t, --tail                     Tails the build log to the current terminal
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

* [jx start](/commands/jx_start/)	 - Starts a process such as a pipeline

###### Auto generated by spf13/cobra on 9-Aug-2019