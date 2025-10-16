---
layout: resume
title: /resume

# Resume stuff
profile: |- # preserve newlines, no newline at end
  I’m a seasoned reliability engineer with over 18 years of experience scaling global infrastructure across bare metal and cloud. I lead through crises with calm precision, resolving security breaches, datacenter outages, and platform-wide incidents. I bring deep expertise in automation, infrastructure as code (IaC), and continuous integration and delivery (CI/CD), with a track record of building resilient systems at scale, including AWS Interactive Video Service (IVS) which streams trillions of minutes annually. I’m trusted to drive reliability strategy, lead teams through chaos, and engineer systems that don’t fail twice.

jobs:
  - company: Together AI
    title: Staff Site Reliability Engineer
    location: San Francisco, CA
    dates:
      start: Jun 2024
      end: Oct 2025
    description: |-
      As a founding SRE, I helped grow the SRE team from inception to 10+ engineers in my first eight months while fostering a collaborative, inclusive culture. I led automation initiatives across the stack, building Ansible playbooks and multi-cloud Terraform modules that accelerated infrastructure provisioning and reduced manual efforts.

      Together.ai is an AI infrastructure platform / cloud provider specialized for generative AI and large model workloads. They combine high-performance GPU clusters with optimized software, tooling and research innovations, enabling users to train, fine-tune, and deploy models more affordably and efficiently, while preserving flexibility and control.
    duties:
      - Consolidated legacy Ansible playbooks into unified roles, cutting cluster provisioning from days to hours and reducing customer complaints and support tickets
      - Partnered across teams to unblock product launches, enabling audit, billing, and finance features that cut customer billing from days to minutes
      - As final point of escalation, I authored and presented 20 customer facing Root Cause Analysis (RCAs) for high severity incidents
      - Directly guided customers on operational solutions, improving uptime and satisfaction
      - Modernized a large Go codebase and added GitHub Actions CI/CD pipelines, reducing friction and improving developer velocity
      - Architected a multi-region network overlay across cloud and on-prem environments, providing secure access to 10K hosts across 5+ datacenter providers
      - Adopted ArgoCD and related tooling, cutting new Kubernetes cluster deployment time from multiple days to under two hours
      - Converted Kubernetes resources into Helm charts and deployed them via ArgoCD to ensure uniformity across 20+ clusters
      - Optimized GPU provisioning workflows, reducing machine onboarding and offboarding time from days to minutes
      - Diagnosed and resolved complex issues with bleeding-edge NVIDIA hardware and InfiniBand fabrics, reducing production downtime
      - Optimized cloud architecture patterns which reduced provisioning time and increased reliability of customer rented clusters
      - Streamlined EKS cluster provisioning with Terraform and centralized configurations, reducing setup time across regions and environments from days to minutes

  - company: Hive AI
    title: Senior Site Reliability Engineer
    location: San Francisco, CA
    dates:
      start: Jul 2023
      end: Jun 2024
    description: |-
      Modernized legacy automation and provisioning systems while introducing safety guardrails and scalable workflows. I delivered a stateless PXE boot solution for all bare-metal machines (10K), accelerating infrastructure provisioning and improving reliability. I mentored team members on operational excellence and automation best practices, fostering a culture of proactive reliability and maintainability.
    duties:
      - Implemented a stateless PXE boot system, transforming bare-metal provisioning from a serial multi-hour process to a parallelized workflow completed in minutes.
      - Automated routine operational tasks, freeing engineering time and reducing manual effort from multiple days to a few minutes per machine
      - Mentored team members on automation and operational best practices, improving team efficiency and reliability awareness
      - Collaborated across teams to support product launches and resolve escalated production issues

  - company: Twitch
    title: Senior Systems Development Engineer / Site Reliability Engineer
    location: San Francisco, CA
    dates:
      start: Nov 2013
      end: Mar 2023
    description: |-
      Initially part of a 3-person operations team, I advocated for automation and operational excellence. I developed most of the Puppet configuration management, provisioning and monitoring systems, reducing new datacenter build and deployment time from multiple days to a few hours. This facilitated Twitch's growth demands, which started out as a single datacenter and grew to 90+ datacenters.
      In addition to on-call operations and troubleshooting, I mentored interns, developers, and operations staff. My earlier baremetal datacenter experience was instrumental in designing and scaling essential infrastructure such as DNS, DHCP, LDAP, and HTTP Proxies (Squid).
      Later, I shifted focus to writing critical core services which would support cross organizational operational processes.
    duties:
      - Designed, implemented and scaled Hashicorp Consul to 90+ datacenters, and 50K+ hosts, in an automatable and maintainable way
      - Mentored and guided software and operations engineers to level up their skills and understanding of best practices around operational maintainability
      - Aided and guided troubleshooting during impactful outages
      - Worked with skip-level directors and VPs on operational vision and direction
      - Migrated legacy baremetal services to AWS, generally necessitating new design patterns
      - Designed and built network monitoring and alerting services for Anycast IP addressing
      - Researched new technologies and designed PoCs to reduce technical debt and operational toil
      - Built and deployed a baremetal Secrets Management system
      - Negotiated, procured and configured IPAM appliances

  - company: UserVoice, Inc.
    title: Head of Operations
    location: San Francisco, CA
    dates:
      start: Apr 2011
      end: Nov 2013
    description:
      Build, scale, and maintain operations of production SaaS product for 100,000+ customers.
    duties:
      - Capacity Planning
      - Manage Remote Hardware
      - Maintain/Support/Contribute to Production Codebase
      - Site Reliability and Performance

  - company: Friendster, Inc.
    title: System Administrator
    location: Mountain View, CA
    dates:
      start: Jul 2007
      end: Jul 2011
    description:
      Build, install, and maintain 2000+ servers in a data center.
      Maintain and expand both the edge network and internal networks.
    duties:
      - Manage Data Center
      - Meet/Negotiate with Vendors
      - Write Automation Scripts
      - Build/Design Inventory System using Python/Django
      - Manage High Availability Database Architecture and Replication

skills:
  - Programming:
    - Golang
    - Python
    - Ruby
    - PHP
    - Perl
  - Cloud Providers:
    - AWS
    - OCI
    - GCP
    - Crusoe
    - Vultr
  - Virtualization:
    - KVM (qemu)
    - Xen
    - VMWare (ESXi, Server)
  - Containerization:
    - Kubernetes (k8s)
    - Docker
    - Podman
  - Distributed Databases:
    - Consul
    - Zookeeper
    - etcd
  - Infrastructure as Code (IaC):
    - Terraform
    - CDK
  - Configuration Management:
    - Puppet
    - Chef
    - Ansible
  - Linux / Unix Distributions:
    - Debian / Ubuntu
    - RedHat (CentOS)
    - Arch
    - Gentoo
    - Slackware
    - FreeBSD
  - Services:
    - DNS (Bind9, NSD, Unbound)
    - DHCP
    - OpenVPN
    - NFS
    - OpenLDAP (slapd)
  - Webservers / Load Balancers:
    - Traefik
    - Nginx
    - Haproxy
    - Apache
    - Tomcat
  - Datastores:
    - DynamoDB
    - MySQL
    - Redis
    - Riak
    - MemcacheD
    - MongoDB
    - PostgreSQL
  - Monitoring / Observability:
    - Grafana
    - Prometheus
    - Nagios
    - Ganglia
    - Cacti
    - Collectd

---
