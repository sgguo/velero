---
title: "ark restore create"
layout: docs
---

Create a restore

### Synopsis


Create a restore

```
ark restore create BACKUP
```

### Options

```
      --label-columns stringArray            a comma-separated list of labels to be displayed as columns
      --labels mapStringString               labels to apply to the restore
      --namespace-mappings mapStringString   namespace mappings from name in the backup to desired restored name in the form src1:dst1,src2:dst2,...
      --namespaces stringArray               comma-separated list of namespaces to restore
  -o, --output string                        Output display format. For create commands, display the object but do not send it to the server. Valid formats are 'table', 'json', and 'yaml'.
      --restore-volumes                      whether to restore volumes from snapshots
  -l, --selector labelSelector               only restore resources matching this label selector (default <none>)
      --show-labels                          show labels in the last column
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --kubeconfig string                Path to the kubeconfig file to use to talk to the Kubernetes apiserver. If unset, try the environment variable KUBECONFIG, as well as in-cluster configuration
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [ark restore](ark_restore.md)	 - Work with restores

