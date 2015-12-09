# Initial Meetup Kickoff

I want to thank everyone for attending the our kickoff meeting. I would like to formally change the name to CCOG (Charlotte Container Orchestration Group), which will allow us to talk about the various container orchestration platforms; Docker Swarm, Kubernetes and Mesos to name a few. Eventually, I will be inviting vendors to discuss their solutions to the general group. One of our first vendors in February is Docker, who will speak about their upcoming Universal Control Plane (formally Orca).

# Meetup Format

The format for the meetups will be simple:
Each meeting will be roughly one hour. The first 20-30 minutes will be presentation-based. The remainder of the time will be dedicated towards leader-lead walkthroughs. My goal is to have everyone walking away with code, a POC, demonstration, trial (from a vendor) or some other tangible take-away from the class. Additionally, I would like the "leader-lead" sessions to be informative, but not too complex. If it can be coded easily for the rest of the group, that would be great!

Please bring questions! Some of the material is high level. Some information could be repeated from other presentations; that's perfectly fine. I would like to strengthen our Charlotte community, and I think this is a great way to get everyone on the same level quickly (referring to the tangible walk-throughs)

## Agenda

The agenda today is going to cover a lot, because we have a wide-range of interest. The audience is mixed with Application Developers (who are already familiar with Docker), Network Engineers, Network Security Engineers and Staffing Resources who want to know more about this technology, so they know how to better place talent when tasked with the requirements.

Towards the end of the meeting, I would like to cover a few things:
* Reoccurring Meetup times (ex. First Weds of the month)
* Next months speaker (if nobody, then I would like to determine a topic that would be useful for the group)
* Host for next months Meetup
* Possible vendor that could speak with the group at large

Taking this into consideration, here are some details on the slide presentation and tangible take-aways:

##### Presentation:
**TITLE:** Container Orchestration - How a Network Security Architect Started to Use and Deploy Containers
**AUDIENCE:** Application Developers working with their Network Security Architecture team to deliver a secure container orchestration platform

* Overview of Docker
* Docker Popularity (in Production)
* Light Overview on How to Create Containers
* Container Networking and Security Considerations
 * Deeper Look at Docker Networking
 * Understanding the Impacts and Predictive Control Points
* The Orchestration Stack (key elements that make up the stack)
* How Containers are used in Production
* Overview of the Orchestration Stack Workflow
* Looking at the Container Support Stack

##### Walk-through Material:
The walk-through will show a Terraform Deployment of a Kubernetes Stack in Openstack, and deep-dive into the Kubernetes architecture, with a focus on the networking/firewall aspects of the hosts/containers.

##### Take-Away Material:
You'll have a few things after the meetup.
1. Consul Docker Container: I built a consul service discovery container, and uploaded this up Docker Hub for your use.
2. Shipyard Docker Containers: I will show you how to launch and use Shipyard.
3. Kubernetes-Terraform Deployment on Openstack: For those of you with access to Openstack, I have created a terraform deployment that you can use to launch a Kubernetes deployment (and modify it to your needs).
4. Kubernetes-Docker via Hyerkube: I will show others how to launch hyperkube and run a k8s cluster by just using a standard Docker host.

That's all we have this meeting! That's a lot of information.

Brandon
