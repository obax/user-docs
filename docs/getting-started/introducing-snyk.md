# Introducing Snyk

## What is Snyk?

Snyk is a platform allowing you to scan, prioritize, and fix security vulnerabilities in your own code, open source dependencies, container images, and Infrastructure as Code (IaC) configurations.

### Snyk’s developer-first approach

Developers now assemble applications with a combination of proprietary and open source code, run that code in containers, and then deploy with infrastructure as code configurations with technologies like Kubernetes and Terraform.

A good security process secures each of these components where they are built and maintained. Snyk integrates into DevOps processes to work the with developers using the methods each prefers, while following and supporting industry best practices. Snyk integrates directly into your IDEs, workflows, and automation pipelines to add security expertise to your toolkit.

![](<../.gitbook/assets/image (70).png>)

### Snyk products: Use Snyk in your workflow:

* **Secure your code**: use [Snyk Open Source](../products/snyk-open-source/) to fix vulnerabilities in your open source dependencies, and [Snyk Code](../products/snyk-code/) to fix vulnerabilities in your source code.
* **Secure your containers**: use [Snyk Container](../products/snyk-container/) to fix vulnerabilities in container images and Kubernetes applications
* **Secure your deployment**: and [Snyk Infrastructure as Code (IaC)](../products/snyk-infrastructure-as-code/) to fix misconfigurations in Terraform, CloudFormation, Kubernetes, and Azure templates. Use [Snyk Cloud](../products/snyk-cloud/) to fix misconfigurations in Amazon Web Services and Google Cloud accounts in the cloud.

### Snyk environments: choose how to run Snyk

You can run Snyk in the following ways:

* [**Web**](../snyk-web-ui/): the Snyk Web UI ([app.snyk.io](https://app.snyk.io)) provides a browser-based experience, along with functions such as configuration settings, filtering and fixing discovered issues, and reports.
* [**CLI**](https://docs.snyk.io/snyk-cli): the Snyk Command Line Interface enables you to run vulnerability scans on your local machine and integrate Snyk into your pipeline.
* [**IDEs**](../ide-tools/): the Snyk IDE integrations enable you to embed Snyk in your development environment.
* [**API**](https://support.snyk.io/hc/en-us/categories/360000665657-Snyk-API): the Snyk API enables you to programmatically integrate with Snyk, tuning Snyk’s security automation to your specific workflows.

For example, in the Snyk CLI:

{% embed url="https://snyk.io/wp-content/uploads/Homepage-IDE-animation-Log4Shell-FINAL.mp4" %}
Running Snyk from the command line.
{% endembed %}

### How can Snyk work in my environment?

[Snyk products](broken-reference/) support multiple languages and formats:

* **Snyk Open Source**: see [Open Source - Supported languages and package managers](../products/snyk-open-source/language-and-package-manager-support/).
* **Snyk Code**: see [Snyk Code - Supported languages and frameworks](../products/snyk-code/snyk-code-language-and-framework-support.md).
* **Snyk Container**: see [Supported operating system distributions.](../products/snyk-container/supported-operating-system-distributions.md)
* **Snyk Infrastructure as Code**: [Snyk IaC ](../products/snyk-infrastructure-as-code/)supports configuration files for HashiCorp Terraform, AWS CloudFormation, Kubernetes, and Azure Resource Manager (ARM).
* **Snyk Cloud:** [Snyk Cloud](../products/snyk-cloud/) supports scanning [Amazon Web Services resources](../products/snyk-cloud/supported-aws-resources-for-snyk-cloud.md) and [Google Cloud resources](../products/snyk-cloud/getting-started-with-snyk-cloud-google/).

### What can Snyk integrate with?

Snyk integrations for your software development process allow you to integrate Snyk with multiple areas into your development and security processes, including source control, CI/CD, and many others.

See [Snyk integrations](https://docs.snyk.io/integrations) for more details.

### **What does it cost?**

Snyk has several [pricing plans](https://snyk.io/plans/) available, from free to Enterprise.

See [Snyk Pricing Plans](../Snyk-processes/plans.md) for more details.

### What happens to my data?

See [How Snyk handles your data](https://docs.snyk.io/more-info/how-snyk-handles-your-data) for details of Snyk data handling.
