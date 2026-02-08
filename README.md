# Azure-suricata-ids-SOC-Lab
Cloud SOC lab using Azure Sentinel and Suricata IDS for detection and incident response
# Azure SOC Lab — IDS & Sentinel

## Objective
Simulate a cloud SOC environment in Azure, collecting and analyzing network and host logs, detecting attacks, and responding to incidents.

## Tools
- Azure Virtual Machines (Linux & Windows)
- Azure Sentinel (SIEM)
- Suricata IDS
- NSG Flow Logs
- Nmap (attack simulation)
- SSH (authentication logs)

## Lab Steps
1. Deployed Linux VM (`SOC-Linux-IDS`) and Windows SOC VM
2. Enabled NSG Flow Logs & Network Watcher
3. Installed Suricata on Linux VM
4. Simulated attacks:
   - SSH brute-force attempts
   - Nmap port scans
5. Collected and analyzed logs in Suricata and Azure Sentinel
6. Responded:
   - Blocked malicious IPs via NSG rules
   - Documented incidents
7. Created dashboards and KQL queries in Sentinel

## Key Skills Demonstrated
- Threat detection and investigation
- IDS and firewall analysis
- Azure Sentinel KQL queries
- Network and host log correlation
- Incident response workflows
- SOC alert triage
1. **VM Deployment**
   - Deployed Linux VM (`SOC-Linux-IDS`) and Windows SOC VM.
   - Screenshot:  
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/864520f4-9cae-4cf8-acdf-65c339b47ef6" />

2. **Network Logging**
   - Enabled NSG Flow Logs & Network Watcher.
   - Screenshot:  
<img width="867" height="661" alt="image" src="https://github.com/user-attachments/assets/765f51fa-2611-4edc-b2d9-4be604bfd68a" />

3. **Install IDS**
   - Installed Suricata on Linux VM to monitor traffic configure rule.
   - Screenshot:  
<img width="844" height="730" alt="image" src="https://github.com/user-attachments/assets/671b1c04-f1f1-484a-93f0-f7046ca64a9d" />

4. **Simulate Attacks**
   - SSH brute-force attempts from Windows SOC VM.
   - Nmap port scans targeting Linux VM.
   - Screenshot:  
<img width="860" height="700" alt="image" src="https://github.com/user-attachments/assets/801161ea-874b-4084-9b7d-d85e225865f9" />

5. **Detection & Investigation**
   - Monitored Suricata alerts and Azure Sentinel dashboards.
   - Screenshot:  
<img width="845" height="721" alt="image" src="https://github.com/user-attachments/assets/de0066e7-a289-411c-84b2-cd61febf8d4d" />
   - Screenshot:  
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/53aae02e-a416-45b1-b4b9-77a6197cd9bf" />

## Screenshots & Evidence
<img width="873" height="698" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/9da797b3-703c-4289-9cff-960dae5260b5" />
<img width="899" height="637" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/538325d1-adbc-459c-92de-8e580479c8ac" />
<img width="1008" height="593" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/d76fdd00-c19c-4437-96a9-9a310ee86e95" />
<img width="860" height="700" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/be238827-9029-41bf-9483-c669ff13aea5" />
<img width="1025" height="562" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/0e07fa41-90d3-4203-a959-3e1407a6d357" />
<img width="1366" height="768" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/ac774348-fca2-42ac-ad0c-70fbce1c2a42" />
<img width="867" height="661" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/904a653a-7225-40c5-b8e5-74c79844ed45" />
<img width="1366" height="768" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/44ef266b-3a08-4183-85dc-3970ca0b17d9" />
<img width="1366" height="768" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/f9c44d6c-c64c-45df-9cc0-e622a361a673" />
<img width="1366" height="768" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/5c28b6d9-f3bc-4a02-9931-3cff9ba77279" />
<img width="845" height="721" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/799446a6-1d6d-491e-b7e1-a21ea635c012" />
<img width="844" height="730" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/f9b7c097-3a6e-425f-9a0f-7205c38ecb73" />
<img width="897" height="653" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/18c9509d-a2aa-43a5-908b-9a02564e9ed2" />


