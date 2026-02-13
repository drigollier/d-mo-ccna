#configuration a faire sur le switch de distribution
#configuration du fastEthernet 0/1
interface fastEthernet 0/1
switchport mode access
switchport access vlan 10
#configuration du fastEthernet 0/2
interface fastEthernet 0/2
switchport mode access
switchport access vlan 30
#configuration du fastEthernet 0/3
interface fastEthernet 0/3
switchport mode access
switchport access vlan 10
#configuration du fastEthernet 0/4
interface fastEthernet 0/4
switchport mode access
switchport access vlan 30
