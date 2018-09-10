## HPE Docker Volume Plugin for HPE 3PAR StoreServ

HPE Docker Volume Plugin is an open source project that provides persistent storage and features for your containerized applications using HPE 3PAR StoreServ Storage arrays.

The HPE Docker Volume Plugin supports popular container platforms like Docker, Kubernetes, OpenShift and soon SuSE CaaS/CAP (coming in v3.0)

## HPE Docker Volume Plugin Overview

Before we get started, you need to make a choice on how you will be using the plugin.

#### Standalone Docker instance

Here is an example of the plugin being used in a standalone Docker instance:

![HPE Docker Volume Plugin](https://github.com/budhac/python-hpedockerplugin/blob/master/docs/img/3PAR_docker_design_diagram_75.png)


#### Kubernetes/OpenShift environment

Here is an example of the plugin being used in OpenShift environment:

![HPE Docker Volume Plugin with OpenShift](https://github.com/budhac/python-hpedockerplugin/blob/master/docs/img/3PAR_k8_design_diagram_75.png)

## Install and Quick Start instructions

* Review the [System Requirements](/docs/system-reqs.md) before installing the plugin
* Check out the [Quick Start Guide](/docs/quick_start_guide.md) for deploying the HPE Docker Volume Plugin in Docker or in Kubernetes/OpenShift environments


## Supported Features

* Fibre Channel & iSCSI support for 3PAR
* Secure/Unsecure etcd cluster for fault tolerance
* Advanced volume features
  * thin
  * dedup
  * full
  * compression
  * snapshots
  * clones
  * QoS
  * snapshot mount
  * mount_conflict_delay
  * concurrent volume access

## Usage

See the [usage instructions](/docs/usage.md) for details on the supported operations and usage of the plugin.

## Troubleshooting

Troubleshooting issues with the plugin can be performed using these [tips](/docs/troubleshooting.md)

## Contributions

This section describes steps that should be done when creating contributions for this plugin.

Review the [Contribution instructions](/docs/contribute.md)
