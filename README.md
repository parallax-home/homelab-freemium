# homelab-freemium
A reference for software you might use at work but has a free or low cost version you can use in a home lab. Also a way to find commercial products which are a lower cost but functionally similar alternative to full priced commercial software. Mostly these are not open source and some are not self hosted either.

This is only for products which are free or heavily discounted for home or lab use, and does not inlcude time limited free trials of commercial software.

Hypervisors

- VMware VSphere - most functions available with a VMUG licence (~$180-200/yr). Free ESXi does not have API enabled.
- Proxmox - Commercial version is the same, but with support.
- xcp-ng - Commercial version is the same, but with support. Xen Orchestra Appliance (XOA) is a GUI management appliance which requires paid licence for many useful feaures. Can compile yourself instead or use a pre-compiled Docker image.
- Rancher Harvester - Commercial version is the same, but with support. A bundle of KubeVirt, Rancher, and Longhorn, plus some others. Run VMs and k8s comtainers in a single environment. 
- Nutanix - Requires 4+ cores / 16+GB RAM minimum (32GB preferred), 200+GB SSD / 500+GB spinning disk, must be three disks per node, ideally identical nodes. 1, 3, or 4 node cluster supported. HCI platform.

Firewalls
- Sophos XG - Free for home use, supports up to 4 cores (not threads) and 6GB of RAM. Commercial version is functionally the same, but with support. Fairly well featured NGFW albeit with limitaions compared to market leaders.

SDWAN / SSE
- FlexiWAN - Free for up to 3 edge instances in a shared environment.

Automation
- Automation Anywhere - Robotic Process Automation.

Security
- Contrast - secure one Java or .Net application in dev and prod.
- Qualys - limited to vulnerability scanning of 16 internal and 3 external assets, plus one URL. IT asset management and compliance.
- Tenable Nessus - limited to scanning 16 IPs.

Logging
- Humio - 16GB/day, 7 day retention indexing allowed.
- Splunk - 500MB/day, no indexing or alerting. 10GB/day for developers license (https://dev.splunk.com/enterprise/dev_license/), even with a personal email address, anecdotally gets bumped to 50GB/day if your employer is a Splunk customer (use your work address).

Backup
- Arcserve UDP - Up to 1TB of workloads backed up in the Community Edition.
- Veeam Availability Suite - NFR version available (https://go.veeam.com/free-nfr-veeam-availability-suite).

Database migration
- Redgate Flyway.

Data analysis
- Databricks - Limited to 15GB clusters.

Process Management
- Alfresco Activiti.

Content Management
- Alfresco 

Low Code
- Appian
