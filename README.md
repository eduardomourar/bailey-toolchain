# Bailey Toolchain

This toolchain will allow you to deploy [Bailey](https://github.ibm.com/cds-sre-org/bailey) tool into Bluemix

## Create the toolchain

1. Ensure you have 1GB of free memory and space for 2 additional services in your organization.

1. It is recommended to create a new space in your organization. This helps grouping the apps and services together in the console.

1. **To get started, click this button:**

  [![Deploy To Bluemix](./.bluemix/create_toolchain_button.png)](https://console.w3ibm.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/eduardomourar/bailey-toolchain.git)

  > :warning: Make sure to pick unique application names in the Delivery Pipeline step.

The toolchain is preconfigured for:

- source control
- online editing
- continuous delivery (CD)
- blue-green deployment

---
### Learn more

* [Bluemix DevOps Services][bluemix_devops_url]
* [Bluemix Toolchains Documentation][toolchains_overview_url]

<!--Links-->
[bluemix_devops_url]: https://console.w3ibm.bluemix.net/devops
[toolchains_overview_url]: https://console.ng.bluemix.net/docs/toolchains/toolchains_overview.html
