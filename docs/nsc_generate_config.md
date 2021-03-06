## nsc generate config

Generate an account config file for an operator

### Synopsis

Generate an account config file for an operator

```
nsc generate config [flags]
```

### Examples

```
nsc generate config --mem-resolver
nsc generate config --mem-resolver --config-file <outfile>
nsc generate config --mem-resolver --config-file <outfile> --force

```

### Options

```
      --config-file string   output configuration file '--' is standard output (exclusive of --dir) (default "--")
  -F, --force                overwrite output files if they exist
  -h, --help                 help for config
      --mem-resolver         generates a mem resolver server configuration
      --sys-account string   system account name
```

### Options inherited from parent commands

```
  -i, --interactive          ask questions for various settings
  -K, --private-key string   private key
```

### SEE ALSO

* [nsc generate](nsc_generate.md)	 - Generate activations, creds, configs or nkeys

###### Auto generated by spf13/cobra on 26-Nov-2019
