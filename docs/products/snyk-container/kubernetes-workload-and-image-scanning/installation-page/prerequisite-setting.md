# Prerequisite setting

{% hint style="info" %}
**Feature availability**\
This feature is available with all paid plans. See [pricing plans](https://snyk.io/plans/) for more details.
{% endhint %}

Before installing Snyk Controller, make sure you have the prerequisites:

* You must have an administrator account for your Snyk organization.
* You must have a minimum of 50 GB of storage available in the form of an [emptyDir](https://kubernetes.io/docs/concepts/storage/volumes/#emptydir) on the cluster.
* You must have a minimum of the indicated RAM requirements to run on the cluster.

```
requests: cpu: "250m" memory: "400Mi"
limits: cpu: "1" memory: "2Gi"
```

* Your Kubernetes cluster must be able to communicate with Snyk outbound over HTTPS.
* [Enable the Kubernetes Integration ](../kubernetes-integration-overview/viewing-your-kubernetes-integration-settings.md)to get your **Integration ID**.
* Install [Helm](https://helm.sh/docs/intro/install/) locally

If you are using Snyk deployed in an alternative datacenter (for example, MT-EU or MT-AU) you will need to to change the upstream endpoint URL through an environment variable as follows, Modify the URL as needed for your specific deployment.

* AU: [https://api.au.snyk.io/v1/kubernetes-upstream](https://api.au.snyk.io/v1/kubernetes-upstream)
* EU: [https://api.eu.snyk.io/v1/kubernetes-upstream](https://api.eu.snyk.io/v1/kubernetes-upstream)
* Helm example: `--set integrationApi=`[`https://api.au.snyk.io/v1/kubernetes-upstream`](https://api.au.snyk.io/v1/kubernetes-upstream)``
