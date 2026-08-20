# awesome-rancher with stars

[<img src="https://rancher.com/img/farm-k8s.svg">](https://rancher.com/img/farm-k8s.svg)

A curated list of awesome Rancher resources inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 498,070 | 🐛 105 | 📅 2026-08-18 list.

If you see a link that isn't a good fit, you can fix it by submitting a pull request to help improve the list. Likewise, if you'd like to add or fix something, click the [README.md](README.md) file to edit and submit a pull request.  Thank you!

## What is Rancher?

> Rancher is an open source software platform that enables organizations to run containers in production. With Rancher, organizations no longer have to build a container services platform from scratch using a distinct set of open source technologies. Rancher supplies the entire software stack needed to manage containers in production.

# Contents

* [Getting started](#getting-started)
* [Resources](#resources)
* [Rancher 2.0](#rancher-20)
  * [Blog posts](#blog-posts)
  * [Community projects](#community-projects)
  * [How-tos](#how-to)
* [Rancher 1.0](#rancher-10)
  * [Blog posts](#blog-posts-10)
  * [Tools](#tools-10)
  * [Community projects](#community-projects-10)
    * [Terraform](#terraform)
    * [Chef](#chef)
    * [Third party](#third-party)
* [Twitter accounts to follow](#twitter-accounts-to-follow)
* [Connect with Rancher](#connect-with-rancher)
* [Contributing](#contributing)

## Getting started

* [Rancher OS docs](https://rancher.com/docs/os/v1.x/en/)
* [Rancher 1.x docs](https://rancher.com/docs/rancher/v1.6/en/)
* [Rancher 2.x docs](https://rancher.com/docs/rancher/v2.x/en/)
* [Try Rancher](https://try.rancher.com)

## Resources

* [Project Plan](https://github.com/rancher/rancher/wiki/Rancher-Project-Plan) ⭐ 25,862 | 🐛 3,353 | 🌐 Go | 📅 2026-08-20
* [Installing Rancher Server](https://docs.rancher.com/rancher/installing-rancher/installing-server/)
* [Upgrading Rancher Server](https://docs.rancher.com/rancher/latest/en/upgrading/)
* [Environments](https://docs.rancher.com/rancher/v1.5/en/environments/)
* [Hosts](http://docs.rancher.com/rancher/v1.5/en/hosts/)
* [Registries](https://docs.rancher.com/rancher/v1.5/en/environments/registries/)
* [Working with Cattle](http://docs.rancher.com/rancher/v1.5/en/cattle/stacks/)
* [Working with Kubernetes](http://docs.rancher.com/rancher/v1.5/en/kubernetes/)
* [Working with Mesos](http://docs.rancher.com/rancher/v1.5/en/mesos/)
* [Using the catalog](http://docs.rancher.com/rancher/latest/en/catalog/)
* [API Documentation](http://docs.rancher.com/rancher/latest/en/api/)
* [Rancher monitoring with Prometheus](https://github.com/infinityworksltd/Guide_Rancher_Monitoring)

## Rancher 2.0

* [Rancher 2.0 roadmap](https://github.com/rancher/rancher/wiki/Rancher-2.0) ⭐ 25,862 | 🐛 3,353 | 🌐 Go | 📅 2026-08-20
* [Rancher 2.0 catalog](https://github.com/rancher/charts) ⭐ 430 | 🐛 18 | 🌐 Go Template | 📅 2026-08-20
* [Rancher 2.0 Helm Chart](https://github.com/rancher/server-chart) ⚠️ Archived
* [Rancher 2.0](http://rancher.com/rancher2-0/)
* [Getting started guide](http://rancher.com/docs/rancher/v2.0/en/quick-start-guide/)
* [Rancher 2.0 FAQ](http://rancher.com/docs/rancher/v2.0/en/faq/)
* [Rancher 2.0 video demo](https://www.youtube.com/watch?v=Ma6FsuWI2Nc\&feature=youtu.be)
* [Rancher 2.0 technical details](https://cdn2.hubspot.net/hubfs/468859/Whitepapers/Rancher%202.0%20Technical%20Architecture%20-%20Sept%202017.pdf)

### Cloud Drivers

* [Hetzner Cloud UI Driver](https://mxschmitt.github.io/ui-driver-hetzner/)

### Blog posts

* [Kicking the tires on rancher 2.0](https://vadosware.io/post/kicking-the-tires-on-rancher-2.0/)
* [Test Rancher 2.0 using Minikube](https://thepracticalsysadmin.com/test-rancher-2-0-using-minikube/)
* [Managing Kubernetes Workloads with Rancher 2.0](https://rancher.com/managing-kubernetes-workloads-with-rancher-2-0/)
* [SSL/TLS options for Rancher 2.0](https://medium.com/@superseb/ssl-tls-options-for-rancher-2-0-dca483a7070d)
* [Understanding Authentication & Authorization in Rancher 2.0](https://rancher.com/blog/2018/2018-05-04-authentication-authorization-rancher2/)
* [How to run Rancher 2.0 on your desktop](https://rancher.com/blog/2018/2018-05-18-how-to-run-rancher-2-0-on-your-desktop/)
* [Recover Rancher Kubernetes cluster from a Backup](https://rancher.com/blog/2018/recover-rancher-kubernetes-cluster-from-backup/)
* [Load Balancing on Kubernetes with Rancher](https://rancher.com/blog/2018/load-balancing-user-apps-with-rancher/)
* [Installing Rancher 2 HA Cluster with Let’s Encrypt](https://medium.com/@facktoreal/installing-rancher-2-ha-with-lets-encrypt-ca3e09bf19c1)
* [Cluster and Workload Alerts in Rancher 2.0](https://rancher.com/blog/2018/cluster-workload-alerts/)
* [CRDs and Custom Controllers in Rancher 2.0](https://rancher.com/blog/2018/rancher-management-plane-architecture/)
* [Let's unbox Rancher 2.0 (slide deck)](https://www.slideshare.net/linecorp/lets-unbox-rancher-20-v200)
* [Deploying Istio on a Kubernetes Cluster using Rancher 2.0](https://rancher.com/blog/2018/deploying-istio/)
* [Talking Up Kubernetes with Rancher (podcast)](https://thenewstack.io/talking-up-kubernetes-with-rancher)
* [Building a CI/CD Pipeline with Kubernetes using Auto Devops, Rancher, and Gitlab](https://rancher.com/blog/2018/2018-08-07-cicd-pipeline-k8s-autodevops-rancher-and-gitlab/)
* [Using Okta (and other SAML IdPs) with Rancher 2.0](https://mattslifebytes.com/2018/08/15/using-okta-and-other-saml-idps-with-rancher-2-0/)
* [Adding custom nodes to your Kubernetes cluster in Rancher 2.0](https://medium.com/@superseb/adding-custom-nodes-to-your-kubernetes-cluster-in-rancher-2-0-tech-preview-2-89cf4f55808a)
* [Rancher - push to deploy workflow with Keel](https://webhookrelay.com/blog/2018/11/12/rancher-push-to-deploy-workflow/)
* [How To Set Up Multi-Node Deployments With Rancher 2.1, Kubernetes, and Docker Machine on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-multi-node-deployments-with-rancher-2-1-kubernetes-and-docker-machine-on-ubuntu-18-04)
* [Manage Kubernetes locally with RKE DIND](https://the.binbashtheory.com/rke-dind/)
* [Introducing k3s: The Lightweight Kubernetes Distribution Built for the Edge](https://rancher.com/blog/2019/2019-02-26-introducing-k3s-the-lightweight-kubernetes-distribution-built-for-the-edge/)
* [HA Harbor on Azure with Rancher](http://makspostument.com/2019/02/ha-harbor-on-azure-with-rancher)
* [Life on the Edge: A First Look at Rancher’s Lightweight Kubernetes Distro K3s](https://medium.com/parkbee-tech/life-on-the-edge-a-first-look-at-ranchers-lightweight-kubernetes-distro-k3s-15a3aab1f0fb)
* [Pod rescheduling after a node failure with RKE and Kubernetes](https://medium.com/01001101/pod-rescheduling-after-a-node-failure-with-rke-and-kubernetes-ed11cf3dbeb4)
* [Deploy Rancher on Azure for Kubernetes Management](http://www.buchatech.com/2019/03/deploy-rancher-on-azure-for-kubernetes-management)
* [AKS Deployment Automation with Terraform and Multi-AKS Cluster Management with Rancher, AAD Integration and more](https://blog.kubernauts.io/aks-deployment-automation-with-terraform-and-multi-aks-cluster-management-with-rancher-6da9865ad52b)
* [Managing Amazon EKS Clusters with Rancher](https://aws.amazon.com/blogs/opensource/managing-eks-clusters-rancher/)
* [Introducing the Rancher 2 Terraform Provider](https://rancher.com/blog/2019/rancher-2-terraform-provider/)

### Community projects

* [k3s](https://github.com/rancher/k3s) ⭐ 33,768 | 🐛 66 | 🌐 Go | 📅 2026-08-18 - Lightweight Kubernetes. 5 less than k8s.
* [Terraform RKE](https://github.com/yamamoto-febc/terraform-provider-rke) ⭐ 345 | 🐛 51 | 🌐 Go | 📅 2026-07-20 - Terraform provider plugin for deploying kubernetes clusters with RKE
* [Local Rancher Vagrant](https://github.com/rancher/vagrant/tree/rke) ⚠️ Archived - Vagrant file to stand up a Local Rancher install with 3 nodes
* [Check Rancher 2](https://github.com/Napsty/check_rancher2) ⭐ 26 | 🐛 3 | 🌐 Shell | 📅 2025-06-13- Monitoring plugin to check Docker environments in Rancher 2.x
* [rancher-arm64](https://github.com/rancherpi/rancher-arm64) ⭐ 19 | 🐛 0 | 📅 2018-10-08 - Repo to build rancher on arm64 platform
* [RKE Vagrant](https://github.com/flaccid/rke-vagrant) ⭐ 11 | 🐛 0 | 🌐 Ruby | 📅 2018-05-08 - vagrant up RKE (Rancher Kubernetes Engine)
* [Rancher 2.0 Helm Chart](https://github.com/jgreat/helm-rancher-server) ⚠️ Archived - Helm catalog for Rancher 2.0
* [Logspout Rancher Ledger](https://github.com/myENA/logspout-rancher-ledger) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2017-11-30 - A logspout plugin for Rancher v2.0
* [Rancher service registrator for Consul](https://github.com/myENA/rancher-herder) ⚠️ Archived - Rancher service registration for consul
* [Terraform Rancher provider](https://github.com/terraform-providers/terraform-provider-rancher2) ⚠️ Archived - Terraform Rancher2 provider
* [Terraform - Rancher High Availability Installation](https://github.com/anthonyhumphreys/tf-rancher-ha-gcloud) ⭐ 1 | 🐛 2 | 🌐 HCL | 📅 2019-03-09 - Terraform for setting up a Highly Available Rancher installation on Google Cloud

### How to

* [Setup Metrics Server on an existing Kubernetes Cluster Hosted in Rancher](https://github.com/JasonvanBrackel/metrics-server-on-rancher-2.0.2) ⚠️ Archived
* [Build and run Rancher and RKE on ARM](https://gist.github.com/ags131/7bdde11c932ef7a54f44c6decbfd88b8)

## Rancher 1.0

### Blog posts 1.0

* [Rancher blog](http://rancher.com/blog/)
* [DEPLOYING RANCHER HA IN PRODUCTION WITH AWS, TERRAFORM, AND RANCHEROS](https://thisendout.com/2016/12/10/update-deploying-rancher-in-production-aws-terraform-rancheros/)
* [Creating a highly available container orchestration cluster on AWS](https://www.tastycidr.net/rancher-creating-a-highly-available-container-orchestration-cluster-on-ec2/)
* [Configure a Rancher HAProxy health check](https://thepracticalsysadmin.com/configure-a-rancher-haproxy-health-check/)
* [Bootstrap servers to a Rancher environment](https://thepracticalsysadmin.com/bootstrap-servers-to-a-rancher-environment/)
* [Container Clustering with Rancher Server (Part 5) – Automating the deployment of AWS infrastructure and Rancher with Terraform](https://skeltonthatcher.com/blog/container-clustering-rancher-server-part-5-automating-deployment-aws-infrastructure-rancher-terraform/)
* [Docker orchestration with Kubernetes and Rancher](https://crondev.com/docker-orchestration-kubernetes-rancher/)
* [Setting up Symfony continuous deployment using Rancher](https://lekode.com/2017/06/06/setting-up-symfony-continuous-deployment-using-rancher/)
* [OpenFaaS on Rancher](https://medium.com/cloud-academy-inc/openfaas-on-rancher-684650cc078e)

### Tools 1.0

* [Rancher](https://github.com/rancher/rancher) ⭐ 25,862 | 🐛 3,353 | 🌐 Go | 📅 2026-08-20
* [Convoy](https://github.com/rancher/convoy) ⚠️ Archived - A Docker volume plugin, managing persistent container volumes
* [Cattle](https://github.com/rancher/cattle) ⚠️ Archived - Cattle is the orchestration engine that powers Rancher
* [Rancher CLI](https://github.com/rancher/cli) ⭐ 389 | 🐛 16 | 🌐 Go | 📅 2026-08-20 - The Rancher Command Line Interface (CLI)is a unified tool to manage your Rancher server
* [Rancher community catalog](https://github.com/rancher/community-catalog) ⚠️ Archived - The catalog provides templates created and maintained by the community
* [Rancher Compose](https://github.com/rancher/rancher-compose) ⚠️ Archived - Docker compose compatible client to deploy to Rancher
* [Rancher catalog](https://github.com/rancher/rancher-catalog) ⚠️ Archived - The catalog provides templates created and maintained by Rancher

### Community projects 1.0

* [Rancher GitLab deployment tool](https://github.com/cdrx/rancher-gitlab-deploy) ⭐ 428 | 🐛 9 | 🌐 Python | 📅 2021-09-07 - Painless deployment of projects built with GitLab CI onto your Rancher infrastructure
* [Rancher Let's Encrypt](https://github.com/janeczku/rancher-letsencrypt) ⭐ 324 | 🐛 50 | 🌐 Go | 📅 2019-06-14 - Rancher service that obtains and manages free SSL certificates from the Let's Encrypt CA using DNS & webroot verification
* [Rancher cron](https://github.com/SocialEngine/rancher-cron) ⭐ 128 | 🐛 9 | 🌐 Go | 📅 2018-03-22 - A service that can start containers on a defined schedule
* [GitLab CI ready image](https://github.com/kiwicom/crane) ⚠️ Archived - A GitLab CI ready image to upgrade services in Rancher
* [Gaucho](https://github.com/etlweather/gaucho) ⚠️ Archived - A Python CLI tool for Rancher's API
* [Rancher Let's Encrypt](https://github.com/tozny/rancher-lets-encrypt) ⭐ 92 | 🐛 3 | 🌐 Python | 📅 2023-05-22 - Automatically create and manage certificates in Rancher using Let's Encrypt webroot verification via a minimal service
* [Rancher alarms](https://github.com/ndelitski/rancher-alarms) ⭐ 85 | 🐛 22 | 🌐 JavaScript | 📅 2017-08-15 - Send notifications when something goes wrong in rancher
* [Rancher SaltStack deployment](https://github.com/komljen/rancher-salt) ⭐ 42 | 🐛 1 | 🌐 SaltStack | 📅 2017-03-23 - Salt states for Rancher container platform deployment
* [Jenkins Rancher Plugin](https://github.com/jenkinsci/rancher-plugin) ⭐ 38 | 🐛 16 | 🌐 Java | 📅 2020-03-31 - Enables Jenkins to deploy or upgrade Rancher stack service instance
* [Faas Rancher](https://github.com/kenfdev/faas-rancher) ⚠️ Archived - Enable Rancher as a backend for Functions as a Service (OpenFaaS)
* [Rancher reaper](https://github.com/ampedandwired/rancher-reaper) ⭐ 19 | 🐛 2 | 🌐 Ruby | 📅 2017-07-26 - A Service to automatically delete hosts from Rancher if they have been terminated in AWS
* [Rancher Vagrant](https://github.com/nextrevision/rancher-vagrant) ⭐ 18 | 🐛 1 | 🌐 Ruby | 📅 2016-05-28 - Extensible and automated local Rancher environments using Vagrant
* [ChaosRancher](https://github.com/bscott/chaosrancher) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2017-03-24 - ChaosRancher periodically kills random services in your Rancher Stack/Cluster.
* [Rancher zsh completion](https://github.com/go/rancher-zsh-completion) ⭐ 10 | 🐛 5 | 🌐 Shell | 📅 2017-04-12 - zsh completion for Rancher CLI
* [Rancher wrangler](https://github.com/bscott/rancher-wrangler) ⭐ 9 | 🐛 10 | 🌐 Go | 📅 2017-01-24 - Wrangler is a Web Interface to see detailed Information about Rancher Servers
* [Cowpoke](https://github.com/LeanKit-Labs/cowpoke) ⭐ 9 | 🐛 6 | 🌐 JavaScript | 📅 2016-12-06 - A service to handle configurable Rancher service upgrade patterns
* [Cowcheck](https://github.com/cloudnautique/cowcheck) ⭐ 8 | 🐛 4 | 🌐 Go | 📅 2017-12-21 - A microservice for checking the health of a Rancher node
* [Rancher Events](https://github.com/ibrokethecloud/rancher-events) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2017-07-12 - Extract Docker events from Rancher
* [Giddyup](https://github.com/cloudnautique/giddyup) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2017-08-23 - Giddyup is a tool to that helps get services started in a Rancher compose stack
* [Rancher client](https://github.com/aboutdotme/rancher-client) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2018-09-26 - A Rancher API client for containerized deployments and management
* [Vagrant Rancher](https://github.com/SkeltonThatcher/vagrant-rancher) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2017-09-05 - Vagrant files to create a Rancher server and host environment for local development
* [Rancher Prometheus](https://github.com/ecliptik/rancher-prometheus) ⭐ 3 | 🐛 0 | 📅 2017-06-02 - Simple Prometheus Stack Config for Rancher
* [Roundup](https://github.com/crystal-construct/roundup) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2017-06-28 - Query rancher-metadata by label, and return the first, or all of the values
* [Rancher firedrill](https://github.com/srflaxu40/rancher-firedrill) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2017-03-26 - Alarm on stopped containers
* [Rancher status page](https://github.com/Demandbase/rancher-status-page) - Simple status page for Rancher stacks and services
* [Rancher logs collector](https://github.com/leodotcloud/rancher-logs-collector) - Rancher logs collector
* [Rancher autobackup](https://github.com/oscarsix/rancher-autobackup) - Do backups from rancher stacks into a git repository by using rancher api

#### Terraform

* [Terraform Rancher HA](https://github.com/nextrevision/terraform-rancher-ha-example) ⭐ 60 | 🐛 0 | 🌐 HCL | 📅 2017-08-10 - Terraform files for deploying a Rancher HA cluster in AWS
* [Terraform Rancher](https://github.com/cloudnautique/terraform-rancher) ⭐ 27 | 🐛 0 | 🌐 HCL | 📅 2017-04-14 - Templates for building and configuring Rancher management and compute stacks
* [Terraform Rancher DigitalOcean](https://github.com/lunagt/rancher-terraform-digitalocean) ⭐ 24 | 🐛 0 | 🌐 HCL | 📅 2017-03-13 - Terraform module for a Rancher server on Digitalocean.
* [Rancher server single node HA and multi-AZ Rancher hosts in AWS](https://github.com/SkeltonThatcher/aws-terraform-rancher-single-node-ha) ⭐ 19 | 🐛 1 | 🌐 HCL | 📅 2017-04-10 - Terraform scripts to deploy Rancher server single node HA and multi-AZ Rancher hosts in AWS
* [Terraform AWS Rancher HA](https://github.com/chrisurwin/terraform-aws-rancher-ha) ⭐ 14 | 🐛 0 | 🌐 HCL | 📅 2016-08-19 - Terraform module for standing up an AWS Rancher HA instance
* [Rancher HA Deployment](https://github.com/crielly/rancher-ha-aws) - A highly available rancher deployment using AWS

#### Chef

* [RancherNg Cookbook](https://supermarket.chef.io/cookbooks/rancher-ng) - Chef cookbok with LWRP for deploy Rancher server and/or agent.

#### Third party

* [SpotInst](https://spotinst.com) - Manage AWS and GCE Spot Instances Groups with Rancher Integration for automatic removal of infrastructure

## Twitter accounts to follow

* [@CloudNautique](https://twitter.com/CloudNautique)
* [@ibuildthecloud](https://twitter.com/ibuildthecloud)
* [@vincentfiduccia](https://twitter.com/vincentfiduccia)
* [@smw355](https://twitter.com/smw355)
* [@deniseschannon](https://twitter.com/deniseschannon)
* [@Lemonjet](https://twitter.com/Lemonjet)
* [@GuerillaNerd](https://twitter.com/GuerillaNerd)
* [@leodotcloud](https://twitter.com/leodotcloud)
* [@shengliang](https://twitter.com/shengliang)
* [@utter\_babbage](https://twitter.com/utter_babbage)
* [@joshwget](https://twitter.com/joshwget)
* [@SvenDowideit](https://twitter.com/SvenDowideit)
* [@davegetzler](https://twitter.com/davegetzler)
* [@junocake](https://twitter.com/junocake)
* [@JasonvanBrackel](https://twitter.com/JasonvanBrackel)

## Connect with Rancher

* [Events](http://rancher.com/events/)
* [Rancher forums](https://forums.rancher.com/)
* [Twitter](https://twitter.com/Rancher_Labs)
* [Slack](https://slack.rancher.io/)
* [IRC](http://webchat.freenode.net/?channels=rancher)
* [Youtube](https://www.youtube.com/channel/UCh5Xtp82q8wjijP8npkVTBA)
* [Online training](https://attendee.gotowebinar.com/rt/2905734731496917249)
* [The RancherCast](https://www.youtube.com/channel/UCTfoEBv6XaI1nEfWDewj5vQ)

## Contributing

* [Cowpoke](https://github.com/rancher/rancher/wiki/Cowpoke-1:-Getting-Started-with-Rancher) ⭐ 25,862 | 🐛 3,353 | 🌐 Go | 📅 2026-08-20 - Get started developing
* [Rancher documentation repo](https://github.com/rancher/rancher.github.io) ⚠️ Archived
* [Contributing](http://docs.rancher.com/rancher/contributing/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
