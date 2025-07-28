# Lab Setup – Initial Configuration

## Host Machine
- Windows 10 Pro
- VirtualBox 7.0

## VMs
- **DC1 (Windows Server 2019)**
  - Roles: AD DS, DNS, DHCP
  - Domain: lab.local
  - IP: 192.168.10.10 (static)

- **Win10Client**
  - Joined to `lab.local`
  - Receives IP via DHCP
  - Used for help desk simulation

## Next Steps
- Create Organizational Units (HR, IT, Finance)
- Add 5 simulated users to each OU
- Configure GPO to enforce strong passwords and auto-lock
