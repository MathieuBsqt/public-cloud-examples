# Public cloud examples

![Work in progess](./docs/assets/wip.jpg)

Here you find a list of examples that use several OVHcloud [public cloud products](https://www.ovhcloud.com/fr/public-cloud/).

You've developed a new cool feature? Fixed an annoying bug? We'd be happy
to hear from you!

Have a look in [CONTRIBUTING.md](https://github.com/ovh/public-cloud-examples/blob/master/CONTRIBUTING.md)

# 👀 Getting Started

 - [Starting Pack to manage your OVHcloud Services from shell](./basics/README.md)

Follow this tutorial to setup your Public Cloud environment. 

That gives you the procedure to install and use many tools to manage the components described in examples, like Terraform, Ansible, Openstack CLI, OVHcloud API, and more.

# ✍️  Examples

|  | | Resources | App | Necessary tools
|---|---|---|---|---
| **01** This example shows you how to create and access to a virtual machine that is connected to a private network, with [Terraform](https://www.terraform.io). | [![Schema example 01](./img/01.png)](./examples/01) | Private network<br/>Instance<br/>SSH keypair | N/A | Terraform
| **02** This example shows you how to create and access to a virtual machine and a managed MongoDB datbase that are connected to a private network, with [Terraform](https://www.terraform.io), and how to install and use the `mongosh` to access the database from the instance. | [![Schema example 02](./img/02.png)](./examples/02) | Private network<br/>Instance<br/>SSH keypair<br/>MongoDB | mongosh CLI| Terraform<br/>Ansible
| **03** | [![Schema example 03](./img/00.png)](./examples/03) | Private network<br/>Kubernetes<br>MySQL | Wordpress | Terraform<br/>Ansible
| **04** | [![Schema example 04](./img/00.png)](./examples/04) | Private network<br>Instance | Mastodon | Terraform<br/>Ansible

# 🔬 Tools for labs

 - [Create instances with K3s installed on OVHcloud Public Cloud](./labs/labk3s/README.md)

# Related links

 * Contribute: https://github.com/ovh/public-cloud-examples/blob/master/CONTRIBUTING.md
 * Report bugs: https://github.com/ovh/public-cloud-examples/issues

# License

Copyright 2022 OVH SAS

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
