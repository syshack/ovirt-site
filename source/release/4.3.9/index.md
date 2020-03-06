---
title: oVirt 4.3.9 Release Notes
category: documentation
toc: true
authors: sandrobonazzola, lveyde
---

<style>
h1, h2, h3, h4, h5, h6, li, a, p {
    font-family: 'Open Sans', sans-serif !important;
}
</style>

# oVirt 4.3.9 Release Notes

The oVirt Project is pleased to announce the availability of the 4.3.9 Third Release Candidate as of March 05, 2020.

oVirt is a free open-source distributed virtualization solution,
designed to manage your entire enterprise infrastructure.
oVirt uses the trusted KVM hypervisor and is built upon several other community
projects, including libvirt, Gluster, PatternFly, and Ansible.

This release is available now for Red Hat Enterprise Linux 7.7 and
CentOS Linux 7.7 (or similar).


To find out how to interact with oVirt developers and users and ask questions,
visit our [community page]"(/community/).
All issues or bugs should be reported via
[Red Hat Bugzilla](https://bugzilla.redhat.com/enter_bug.cgi?classification=oVirt).
The oVirt Project makes no guarantees as to its suitability or usefulness.
This pre-release should not to be used in production, and it is not feature
complete.


If you'd like to try oVirt as quickly as possible, follow the instructions on
the [Download](/download/) page.

For complete installation, administration, and usage instructions, see
the [oVirt Documentation](/documentation/).

For a general overview of oVirt, read the [About oVirt](/community/about.html)
page.

To learn about features introduced before 4.3.9, see the
[release notes for previous versions](/documentation/#previous-release-notes).

## RELEASE CANDIDATE

In order to install this Release Candidate you will need to enable pre-release repository.

`# yum install `[`http://resources.ovirt.org/pub/yum-repo/ovirt-release43-pre.rpm`](http://resources.ovirt.org/pub/yum-repo/ovirt-release43-pre.rpm)



## What's New in 4.3.9?

### Enhancements

#### oVirt Engine

 - [BZ 1797496](https://bugzilla.redhat.com/1797496) **Add RHCOS os to osinfo - for compatability API between 4.3 to 4.4**

   Feature: 

Support Red Hat CoreOS



Reason: 

Red Hat CoreOS is a new operation system that used mostly for containers solution. This bug only introduce the new operation system as part of back compatibility for 4.3 clusters.



Result: 

It is possible to select Red Hat CoreOS operation system for a VM.


### Bug Fixes

#### oVirt Engine

 - [BZ 1792874](https://bugzilla.redhat.com/1792874) **Hide partial engine-cleanup option [RHV clone - 4.3.9]**


#### VDSM

 - [BZ 1795726](https://bugzilla.redhat.com/1795726) **after_migration is not sent to the guest after migration [RHV clone - 4.3.9]**


### Other

#### oVirt Engine

 - [BZ 1809470](https://bugzilla.redhat.com/1809470) **[HE] ovirt-provider-ovn is non-functional on 4.3.9 Hosted-Engine [RHV clone - 4.3.9]**

   

 - [BZ 1808038](https://bugzilla.redhat.com/1808038) **Unable to change Graphical Console of HE VM. [RHV clone - 4.3.9]**

   


#### oVirt Host Deploy

 - [BZ 1613291](https://bugzilla.redhat.com/1613291) **[text] log says ovirt-ha-agent is starting after HE undeploy but it's actually being disabled and stopped**

   


### No Doc Update

#### oVirt Engine

 - [BZ 1789737](https://bugzilla.redhat.com/1789737) **Import of OVA created from template fails with java.lang.NullPointerException [RHV clone - 4.3.9]**

   

 - [BZ 1782185](https://bugzilla.redhat.com/1782185) **Accessing Storage > Volumes  does not work**

   


#### Contributors

18 people contributed to this release:

	Andrej Krejcir
	Artur Socha
	Asaf Rachmani
	Dominik Holler
	Eli Mesika
	Gal Zaidman
	Lev Veyde
	Liran Rotenberg
	Marcin Sobczyk
	Martin Perina
	Milan Zamazal
	Nir Soffer
	Ravi Nori
	Sandro Bonazzola
	Shani Leviim
	Sharon Gratch
	Vojtech Juranek
	Yedidyah Bar David