## Unit  README: 

### Unit Description

In the second project week, you will work on a Red Team vs. Blue Team scenario in which you will play the role of both pentester and SOC analyst.

As the Red Team, you will attack a vulnerable VM within your environment, ultimately gaining root access to the machine. As Blue Team, you will use Kibana to review logs taken during their Day 1 engagement. You'll use the logs to extract hard data and visualizations for their report.

Then, you will interpret your log data to suggest mitigation measures for each exploit that you've successfully performed.


### Unit Objectives

This week's project will prompt you to apply knowledge of the following skills and tools:

- Penetration testing with Kali Linux.

- Log and incident analysis with Kibana.

- System hardening and configuration.

- Reporting, documentation, and communication.

### Lab Environment

In this unit, Red vs Blue lab environment located in Windows Azure Lab Services is used. RDP into the Windows RDP host machine, Open the Hyper-V Manager to access the nested machines:

- **ELK machine credentials:** The same ELK setup that you created in Project 1. It holds the Kibana dashboards.
    `

**Capstone:** Filebeat and Metricbeat are installed and will forward logs to the ELK machine. 
   - IP Address: `192.168.1.105`
   - Please note that this VM is in the network solely for the purpose of testing alerts.

**Target 1:** Exposes a vulnerable WordPress server.
  - IP Address: `192.168.1.110`

This unit covers portions of the following domains on the Security+ exam:

- 1.0 Attacks, Threats, and Vulnerabilities 
- 2.0 Architecture and Design 
- 3.0 Implementation
- 4.0 Operations and Incident Response 


Day 1:

- [Red Team Vs Blue Team
- [What is Vulnerability Scanning
- [What is a reverse shell

Day 2: 

- [Kibana: Discover Documentation]
- [Kibana: Visualize Documentation]
- [Elasticsearch Reference Documentation]


