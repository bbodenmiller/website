---
title: Flux Ecosystem
description: "Projects that extend and integrate with Flux."
type: page
---

<div class="ecosystem-page">

# Flux Ecosystem

All entries on this page were added by people who worked on these and thus self-identified as being part of the Flux Ecosystem.

{{% alert color="info" title="Join us" %}}
To join this list, please open a PR on [this file](https://github.com/fluxcd/website/blob/main/content/en/ecosystem/index.md).
If you represent an organisation, please add yourself to [the adopters page](/adopters).
We are happy and proud to have you all as part of our community! :sparkling_heart:
{{% /alert %}}

## Products and Services built on top of Flux

### Featured entries

<div class="ecosystem">
{{< cardpane >}}
{{% card header="[Azure](https://docs.microsoft.com/azure/azure-arc/)" %}}
![Azure](./img/azure.png)
{{% /card %}}
{{% card header="[D2iQ Kommander](https://d2iq.com/products/kommander)" %}}
![D2iQ](/img/logos/d2iq.png)
{{% /card %}}
{{% card header="[Giant Swarm](https://docs.giantswarm.io/advanced/gitops/)" %}}
![Giant Swarm](/img/logos/giantswarm.svg)
{{% /card %}}
{{% card header="[Weave GitOps](https://www.weave.works/enterprise-flux/)" %}}
![Weaveworks](/img/logos/weaveworks.png)
{{% /card %}}
{{< /cardpane >}}
</div>

### Complete list

| Vendor      | Product / Service       | Link                                                                                          |
|-------------|-------------------------|-----------------------------------------------------------------------------------------------|
| AWS         | EKS Anywhere            | [Documentation](https://anywhere.eks.amazonaws.com/docs/tasks/cluster/cluster-flux/)          |
| Azure       | AKS + Azure Arc         | [Documentation](https://docs.microsoft.com/azure/azure-arc/)                                  |
| D2iQ        | Kommander               | [Product page](https://d2iq.com/products/kommander)                                           |
| Giant Swarm | Kubernetes Platform     | [Documentation](https://docs.giantswarm.io/advanced/gitops/)                                  |
| Gimlet      | Gimlet                  | [Documentation](https://gimlet.io/concepts/components/)                                       |
| VMware      | Tanzu                   | [Product Page](https://tanzu.vmware.com/tanzu)                                                |
| Weaveworks  | Weave Gitops Enterprise | [Product Page](https://www.weave.works/enterprise-flux/)                            |

## Flux UIs / GUIs

These open source projects offer a dedicated graphical user interface for Flux.

| Source                                                                | Description                                                                                                                                                                                                                                                                                                             |
|-----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [weaveworks/vscode-gitops-tools](https://github.com/weaveworks/vscode-gitops-tools)                             | GitOps Tools for Visual Studio Code: provides an intuitive way to manage, troubleshoot and operate your Kubernetes environment following the GitOps operating model                                                                      |
| [weaveworks/weave-gitops](https://github.com/weaveworks/weave-gitops) | Weaveworks offers a free and open source GUI for Flux under the [weave-gitops](https://docs.gitops.weave.works/docs/intro) project. You can install the Weave GitOps UI using a Flux `HelmRelease`, please see the [get started documentation](https://docs.gitops.weave.works/docs/getting-started/) for more details. |

{{< blocks/flux_ui_galleries >}}

## Flux Extensions

These open source projects extend Flux with new capabilities.

| Source                                                                            | Description                                                             |
|-----------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| [weaveworks/tf-controller](https://github.com/weaveworks/tf-controller)           | A Flux controller for managing Terraform resources.                     |
| [pelotech/jsonnet-controller](https://github.com/pelotech/jsonnet-controller)     | A Flux controller for managing manifests declared in jsonnet.           |
| [kluctl/flux-kluctl-controller](https://github.com/kluctl/flux-kluctl-controller) | A Flux controller for managing [Kluctl](https://kluctl.io) deployments. |

## Integrations

These projects make use of Flux to offer GitOps capabilities to their users.

| Source                                                                                                          | Description                                                                                                                                                                                                                                                     |
|-----------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [23technologies/gardener-extension-shoot-flux](https://github.com/23technologies/gardener-extension-shoot-flux) | Gardener implements the automated management and operation of Kubernetes clusters as a service. With this extension fresh clusters will be reconciled to the state defined in the Git repository by the Flux controller.                                        |
| [DataDog/integrations-extra](https://github.com/DataDog/integrations-extras/tree/master/fluxcd/)                                                       | The Datadog Agent is software that runs on your hosts. It collects events and metrics from hosts and sends them to Datadog, where you can analyze your monitoring and performance data. |
| [fidelity/kraan](https://github.com/fidelity/kraan)                                                             | Kraan is a Kubernetes Controller that manages the deployment of HelmReleases to a cluster.                                                                                                                                                                      |
| [flux-subsystem-argo/flamingo](https://github.com/flux-subsystem-argo/flamingo)                                 | 🚧 Technology preview: FSA (aka Flamingo) is Flux Subsystem for Argo. FSA's container image can be used as a drop-in replacement for the equivalent ArgoCD version to visualize, and manage Flux workloads, along side ArgoCD.                                  |
| [kubevela/kubevela](https://github.com/kubevela/kubevela)                                                       | KubeVela integrates fluxcd well for [Helm Chart delivery](https://kubevela.io/docs/tutorials/helm) and [GitOps](https://kubevela.io/docs/case-studies/gitops), and provide [multi-cluster capabilities](https://kubevela.io/docs/tutorials/helm-multi-cluster). |
| [microsoft/gitops-connector](https://github.com/microsoft/gitops-connector)                                     | A GitOps Connector integrates a GitOps operator with CI/CD orchestrator.                                                                                                                                                                                        |
| [pulumi/pulumi-kubernetes-operator](https://github.com/pulumi/pulumi-kubernetes-operator) | This operator runs [Pulumi programs](https://www.pulumi.com/docs/intro/concepts/project/), and can fetch them via Flux sources |
| [telekom/das-schiff](https://github.com/telekom/das-schiff)                                                     | This is home of Das Schiff - Deutsche Telekom Technik's engine for Kubernetes Cluster as a Service (CaaS) in on-premise environment on top of bare-metal servers and VMs.                                                                                       |
| [weaveworks/eksctl](https://github.com/weaveworks/eksctl)                                                       | The official CLI for creating and managing Kubernetes clusters on Amazon EKS.                                                                                                                                                                                   |
|           |

## Ancillary Tools

The functionality of Flux can be easily extended with ancillary utility tools. Here is a list of tools we like. If yours is missing, feel free to send a PR to add it.

| Source                                                                | Description                                                                                 | Documentation                                                                               |
|-----------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| [jgz/s3-auth-proxy](https://github.com/jgz/s3-auth-proxy)             | Creates a simple basic-auth proxy for an s3 bucket.                                         | [README](https://github.com/jgz/s3-auth-proxy#readme)                                       |
| [raffis/gitops-zombies](https://github.com/raffis/gitops-zombies)     | Identify kubernetes resources which are not managed by GitOps                               | [README](https://github.com/raffis/gitops-zombies#readme)                                   |
| [renovatebot/renovate](renovatebot/renovate)                          | Universal dependency update tool that fits into your workflows.                             | [Automated Dependency Updates for Flux](https://docs.renovatebot.com/modules/manager/flux/) |
| [tarioch/flux-check-hook](https://github.com/tarioch/flux-check-hook) | A [pre-commit](https://pre-commit.com) that validates values of HelmRelease using helm lint | [README](https://github.com/tarioch/flux-check-hook#readme)                                 |

</div>
