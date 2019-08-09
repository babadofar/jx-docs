---
date: 2019-08-09T11:51:15Z
title: "jx step next-version"
slug: jx_step_next-version
url: /commands/jx_step_next-version/
---
## jx step next-version

Writes next semantic version

### Synopsis

This pipeline step command works out a semantic version, writes a file ./VERSION and optionally updates a file

```
jx step next-version [flags]
```

### Examples

```
  jx step next-version
  jx step next-version --filename package.json
  jx step next-version --filename package.json --tag
  jx step next-version --filename package.json --tag --version 1.2.3
  
  # lets use git to create a new version from a tag and tag git
  jx step next-version --use-git-tag-only --tag
```

### Options

```
  -d, --dir string         the directory to look for files that contain a pom.xml or Makefile with the project version to bump
  -f, --filename string    Filename that contains version property to update, e.g. package.json
  -h, --help               help for next-version
      --semantic-release   use conventional commits to determine next version. Ignores the --use-git-tag-only and --version options See https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines
  -t, --tag                tag and push new version
      --use-git-tag-only   only use a git tag so work out new semantic version, else specify filename [pom.xml,package.json,Makefile,Chart.yaml]
      --version string     optional version to use rather than generating a new one
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

* [jx step](/commands/jx_step/)	 - pipeline steps

###### Auto generated by spf13/cobra on 9-Aug-2019