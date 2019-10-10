## ecctl platform stack

Manages Elastic StackPacks

### Synopsis

Manages Elastic StackPacks

```
ecctl platform stack [flags]
```

### Options

```
  -h, --help   help for stack
```

### Options inherited from parent commands

```
      --apikey string      API key to use to authenticate (If empty will look for EC_APIKEY environment variable)
      --config string      Config name, used to have multiple configs in $HOME/.ecctl/<env> (default "config")
      --force              Do not ask for confirmation
      --format string      Formats the output using a Go template
      --host string        Base URL to use (default "https://api.elastic-cloud.com")
      --insecure           Skips all TLS validation
      --message string     A message to set on cluster operation
      --output string      Output format [text|json] (default "text")
      --pass string        Password to use to authenticate (If empty will look for EC_PASS environment variable)
      --pprof              Enables pprofing and saves the profile to pprof-20060102150405
  -q, --quiet              Suppresses the configuration file used for the run, if any
      --region string      Elastic Cloud region
      --timeout duration   Timeout to use on all HTTP calls (default 30s)
      --trace              Enables tracing saves the trace to trace-20060102150405
      --user string        Username to use to authenticate (If empty will look for EC_USER environment variable)
      --verbose            Enable verbose mode
```

### SEE ALSO

* [ecctl platform](ecctl_platform.md)	 - Manages the platform
* [ecctl platform stack delete](ecctl_platform_stack_delete.md)	 - Deletes an Elastic StackPack
* [ecctl platform stack list](ecctl_platform_stack_list.md)	 - Lists Elastic StackPacks
* [ecctl platform stack show](ecctl_platform_stack_show.md)	 - Shows information about an Elastic StackPack
* [ecctl platform stack upload](ecctl_platform_stack_upload.md)	 - Uploads an Elastic StackPack
