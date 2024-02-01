# kubecost-cummins



## Getting started

You need to first run

``` $ oc create ns kubecost```

Before doing anything else.

Then run the following to allow GitOps to be able to deploy in the kubecost namespace.

``` $ oc adm policy add-role-to-user admin system:serviceaccount:openshift-gitops:openshift-gitops-argocd-application-controller```

Afterwards, you should be able to deploy this using Gitops.
