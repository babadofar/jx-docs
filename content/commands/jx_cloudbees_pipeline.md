---
date: 2019-08-09T11:51:15Z
title: "jx cloudbees pipeline"
slug: jx_cloudbees_pipeline
url: /commands/jx_cloudbees_pipeline/
---
## jx cloudbees pipeline

Opens the CloudBees Pipeline page for visualising CI/CD

### Synopsis

Opens the CloudBees Pipeline page for the current App in a browser. 

Which helps you visualise your CI/CD pipelines, apps, environments and teams. 

For more information please see https://www.cloudbees.com/blog/want-help-build-cloudbees-kubernetes-jenkins-x

```
jx cloudbees pipeline [flags]
```

### Examples

```
  # Open the CloudBees Pipeline page in a browser
  jx cloudbees pipeline
  
  # Print the CloudBees Pipeline page URL but do not open a browser
  jx cloudbees pipeline -u
```

### Options

```
  -h, --help   help for pipeline
  -u, --url    Only displays the URL and does not open the browser
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

* [jx cloudbees](/commands/jx_cloudbees/)	 - Opens the CloudBees app for Kubernetes for visualising CI/CD and your environments

###### Auto generated by spf13/cobra on 9-Aug-2019