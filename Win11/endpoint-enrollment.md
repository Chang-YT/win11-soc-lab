# Windows Endpoint Enrollment

connecting Windows 11 VM to the Wazuh server so events show up in the SIEM (Wazuh)

## Environment
- Endpoint: Windows 11 VM (VMware Workstation)
- Wazuh server: Wazuh 4.14.8 on Ubuntu Server 24.04.5 LTS
- Agent: Wazuh Windows agent

## Steps
1 started the Windows 11 VM
2 installed the Wazuh Windows agent
3 configure the agent to the manager IP address
   *Win11 VM and the server need to reach each other
4 enrolled the agent with the manager and started the agent service
5 check on Wazuh dashboard to make sure it is connected

## Result
show **Active** in the dashboard

![Endpoint connected in Wazuh](screenshorts\endpoints.png)
![Wazuh Dashboard](screenshorts\overview.png)