# Deploying OpenShift on IBM Power Systems

Red Hat and IBM Power teams have been working together on OpenShift since 2018 with the initial release of OpenShift 3.11 on Power. Through this continuous collaboration and effort between IBM and Red Hat, the joint venture has enabled Power Systems clients to create new digital experiences that leverage modern cloud-native technologies and extend the value of their existing investments in AIX and IBM i. This Github organization is home to Infrastructure as Code (IaC) patterns to help deploy OpenShift on IBM Power Systems. Terraform is used to create the infrastructure and ansible playbooks are used to deploy and customer OpenShift. The following diagram shows the high level overview of the IaC pattern:

![Automation Architecture](https://github.com/ktania46/image/blob/main/OCPPowerAutomationArchDiag.png?raw=true)

Based on Kubernetes 1.19, OpenShift 4.6 introduced several exciting new capabilities for Power: Extended Update Support (EUS), the first EUS-enabled release in the 4.x stream. Now clients can remain on OCP 4.6 for a longer period of time with enterprise support. Support for compute nodes with up to 512 threads. Clients running scale-up Power Systems nodes (e.g., E980s) can exploit all that compute power, further realizing Power's container density and TCO benefits. Several storage-related enhancements, such as support for 4K sector drives and enablement for additional storage options such as HostPath, iSCSI and local-storage-operator. While this is just a few of the exciting new features in OCP 4.6, it demonstrates how OpenShift continues driving innovation as the leading hybrid cloud platform.

## Contents:

- [Deploying OpenShift on IBM Cloud Power Virtual Servers](powervs.md)
     - Introduction 
     - Automation Host Prerequisites 
     - PowerVS Prerequisites 
     - OCP Install </br>
&nbsp;
- [Deploying OpenShift on KVM](ocp_kvm.md)
     - Introduction 
     - Prerequisites
     - Image and VM Requirements 
     - OCP Install </br>
&nbsp;
- [Deploying OpenShift on PowerVM managed via PowerVC ](powervm.md)
     - Introduction 
     - Prerequisites 
     - Image and LPAR Requirements 
     - OCP Install </br>
&nbsp;

