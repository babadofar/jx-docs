---
date: 2019-08-09T11:51:15Z
title: "jx step git"
slug: jx_step_git
url: /commands/jx_step_git/
---
## jx step git

git [command]

### Synopsis

git [command]

```
jx step git [flags]
```

### Options

```
  -h, --help   help for git
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
* [jx step git close](/commands/jx_step_git_close/)	 - Closes issue trackers, wikis and projects
* [jx step git credentials](/commands/jx_step_git_credentials/)	 - Creates the Git credentials file for the current pipeline
* [jx step git envs](/commands/jx_step_git_envs/)	 - Creates the Git environment variables for the current pipeline Git credentials
* [jx step git fork-and-clone](/commands/jx_step_git_fork-and-clone/)	 - Forks and clones a git repo
* [jx step git merge](/commands/jx_step_git_merge/)	 - Merge a number of SHAs into the HEAD of master
* [jx step git validate](/commands/jx_step_git_validate/)	 - Validates the .gitconfig is correctly configured

###### Auto generated by spf13/cobra on 9-Aug-2019