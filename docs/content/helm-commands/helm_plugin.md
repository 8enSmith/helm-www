+++
title = "helm plugin"
weight = "24"

tags = ["commands"]
section = "helm-commands"
categories = ["helm-commands"]
type = "page"

slug = "helm-plugin"

[menu.main]
  url = "helm-plugin"
  parent = "helm-commands"

+++

## helm plugin

add, list, or remove Helm plugins

### Synopsis



Manage client-side Helm plugins.


### Options inherited from parent commands

```
      --debug                     enable verbose output
      --home string               location of your Helm config. Overrides $HELM_HOME (default "~/.helm")
      --host string               address of tiller. Overrides $HELM_HOST
      --kube-context string       name of the kubeconfig context to use
      --tiller-namespace string   namespace of tiller (default "kube-system")
```

### SEE ALSO
* [helm](helm.md)	 - The Helm package manager for Kubernetes.
* [helm plugin install](helm_plugin_install.md)	 - install one or more Helm plugins
* [helm plugin list](helm_plugin_list.md)	 - list installed Helm plugins
* [helm plugin remove](helm_plugin_remove.md)	 - remove one or more Helm plugins

###### Auto generated by spf13/cobra on 16-Apr-2017