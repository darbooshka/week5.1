# week5.1

To execute stats plugin, run the following command:

```
$ kubectl kubeplugin <namespace> top pod
```

For example, to see statistics for `kube-system` namespace of the current cluster, you can run

```
$ kubectl kubeplugin kube-system top pod
```