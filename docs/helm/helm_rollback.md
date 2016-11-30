## helm rollback

roll back a release to a previous revision

### Synopsis



This command rolls back a release to the previous revision.
The argument of the rollback command is the name of a release.


```
helm rollback [RELEASE]
```

### Options

```
      --dry-run    simulate a rollback
      --no-hooks   prevent hooks from running during rollback
```

### Options inherited from parent commands

```
      --debug                 enable verbose output
      --home string           location of your Helm config. Overrides $HELM_HOME (default "/Users/mattbutcher/Code/helm_home")
      --host string           address of tiller. Overrides $HELM_HOST
      --kube-context string   name of the kubeconfig context to use
```

### SEE ALSO
* [helm](helm.md)	 - The Helm package manager for Kubernetes.

###### Auto generated by spf13/cobra on 1-Nov-2016