---
title: "pgo_show"
---
## pgo show

Show the description of a cluster

### Synopsis

Show allows you to show the details of a policy, backup, pvc, or cluster. For example:

	pgo show backup mycluster
	pgo show backup mycluster --backup-type=pgbackrest
	pgo show benchmark mycluster
	pgo show cluster mycluster
	pgo show config
	pgo show policy policy1
	pgo show pvc mycluster
	pgo show workflow 25927091-b343-4017-be4b-71575f0b3eb5
	pgo show user mycluster

```
pgo show [flags]
```

### Options

```
  -h, --help   help for show
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver.
      --debug                    Enable debugging when true.
      --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo](/cli/pgo/)	 - The pgo command line interface.
* [pgo show backup](/cli/pgo_show_backup/)	 - Show backup information
* [pgo show benchmark](/cli/pgo_show_benchmark/)	 - Show benchmark information
* [pgo show cluster](/cli/pgo_show_cluster/)	 - Show cluster information
* [pgo show config](/cli/pgo_show_config/)	 - Show configuration information
* [pgo show policy](/cli/pgo_show_policy/)	 - Show policy information
* [pgo show pvc](/cli/pgo_show_pvc/)	 - Show PVC information
* [pgo show schedule](/cli/pgo_show_schedule/)	 - Show schedule information
* [pgo show upgrade](/cli/pgo_show_upgrade/)	 - Show upgrade information
* [pgo show user](/cli/pgo_show_user/)	 - Show user information
* [pgo show workflow](/cli/pgo_show_workflow/)	 - Show workflow information

###### Auto generated by spf13/cobra on 23-Jul-2019