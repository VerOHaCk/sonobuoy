## sonobuoy get pod

Fetch sonobuoy pods

### Synopsis

Fetch sonobuoy pods

```
sonobuoy get pod [flags]
```

### Options

```
  -h, --help               help for pod
  -n, --namespace string   The namespace to run Sonobuoy in. Only one Sonobuoy run can exist per namespace simultaneously. (default "sonobuoy")
  -p, --plugin string      Plugin to locate pods for
```

### Options inherited from parent commands

```
      --level level   Log level. One of {panic, fatal, error, warn, info, debug, trace} (default info)
```

### SEE ALSO

* [sonobuoy get](sonobuoy_get.md)	 - Fetches Sonobuoy resources of a specified type

###### Auto generated by spf13/cobra on 14-Nov-2022