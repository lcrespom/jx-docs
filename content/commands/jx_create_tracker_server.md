---
date: 2019-05-11T08:10:08Z
title: "jx create tracker server"
slug: jx_create_tracker_server
url: /commands/jx_create_tracker_server/
---
## jx create tracker server

Creates a new issue tracker server URL

### Synopsis

Adds a new Issue Tracker Server URL

```
jx create tracker server kind [url] [flags]
```

### Examples

```
  # Add a new issue tracker server URL
  jx create tracker server jira myURL
```

### Options

```
  -h, --help          help for server
  -n, --name string   The name for the issue tracker server being created
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx create tracker](/commands/jx_create_tracker/)	 - Creates an issue tracker resource

###### Auto generated by spf13/cobra on 11-May-2019