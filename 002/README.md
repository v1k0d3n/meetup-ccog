# CCOG Meetup 002: January 7th, 2016

There were no formal slides for the CCOG 002 Meetup, although it was a good showing of around 8 people (mostly Red Ventures). Since I didn't have enough time to present this month, we covered details around Kubernetes HA, Etcd HA, general architecture, some best practices scenarios, and other random topics. My "take-home" project for this month was "Terransikube", which is nearly an identical spinoff of the kubernetes/contrib/ansible deployment, just cleaned up a bit. Terransikube was my stop-gap "just get it working" attempt at launching the Openstack IaaS elements, as I work to clean up the [currently not functional] vagrant Openstack/Libvirt/Virtualbox deployment(s).

Eventually, I would like to write Terraform sub-folders to launch IaaC in each of the three/four heavy hitting IaaS providers; Openstack, AWS, Azure (and maybe GCE since GCE has it's own deployment options).

Terransikube can be found (and maintained) at: https://github.com/v1k0d3n/terransikube.
