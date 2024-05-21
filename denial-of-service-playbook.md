# Denial of Service Response Playbook

## Purpose
The Purpose of this document is to describe the steps used to respond to a (distributed) denial of service event.

## Step 1: Preparation
- ISP Support
  * Contact ISP and understand the DDoS mitigation services it provides and what processes they recommend to follow.
- Inventory
  * Create a whitelist of IP addresses and protocols to prioritise during an attack.
  * Document IT infrastructure, including business owners, IP addresses, circuit IDs etc. Have detailed network topologies and an updated asset inventory.
- Network Infrastructure
  * Review network infrastructure and ensure there is no bottle necks or single point of failures.
  * Deploy a Web Application Firewall (WAF) to protect against application-layer DDoS attacks.

## Step 2: Detection and Analysis
- **Detection**: Utilize network monitoring tools and intrusion detection systems to identify abnormal traffic patterns and spikes in traffic.
- **Analysis**: Determine the type and source of the attack (e.g., volumetric, application layer, distributed).

## Step 2: Mitigation
### 2.1 Contact ISP
- Notify your Internet Service Provider about the ongoing attack and request assistance in mitigating the attack closer to its source.
  
### 2.2 Traffic Filtering
- Implement ingress and egress traffic filtering to block malicious traffic at the network perimeter.
- Utilize access control lists (ACLs) and firewalls to drop or rate limit traffic from suspicious sources.
  
### 2.3 Scalability Enhancement
- Scale up bandwidth capacity through traffic scrubbing services or bandwidth upgrades from service providers.
- Deploy content delivery networks (CDNs) to distribute traffic and absorb DDoS attacks.

### 2.4 Application Layer Protection
- Configure web application firewalls (WAFs) to filter and block malicious requests targeting specific application vulnerabilities.
- Harden web and application servers to withstand application layer attacks.

## Step 3: Communication and Coordination
- **Internal Communication**: Notify internal stakeholders including IT teams, network administrators, and executives about the ongoing attack and mitigation efforts.
- **External Communication**: If necessary, communicate with Internet service providers (ISPs), hosting providers, and relevant authorities to coordinate response efforts and potentially block traffic closer to the source.

## Step 4: Incident Response
- **Documentation**: Maintain detailed logs of the attack traffic, mitigation measures, and outcomes for post-incident analysis.
- **Forensics**: Conduct forensic analysis to identify weaknesses in the infrastructure and determine potential points of entry for attackers.
- **Lessons Learned**: Conduct a post-mortem analysis to identify lessons learned and implement improvements to prevent future attacks.

## Step 5: Recovery and Resilience
- **Service Restoration**: Gradually restore services once the attack subsides and verify the integrity of systems before resuming normal operations.
- **Resilience Enhancement**: Implement proactive measures such as redundancy, failover systems, and disaster recovery plans to minimize the impact of future attacks.

## Step 6: Follow-Up
- **Monitoring**: Continuously monitor network traffic and system logs to detect any signs of ongoing or renewed attacks.
- **Updates**: Regularly update security measures, including patches, configurations, and incident response plans, based on emerging threats and lessons learned from previous incidents.

## Additional Resources
- [DDoS Attack Types and Mitigation Techniques](https://www.cloudflare.com/learning/ddos/ddos-attack-tools/)
- [Best Practices for DDoS Protection](https://www.incapsula.com/ddos/ddos-protection-services.html)
