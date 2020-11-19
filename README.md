# Huawei VRP Syntax Highlighting and Snippets

Huawei VRP configuration helper.

## Features

### Syntax highlighting

It draws special attention to different key words
It underlines "display" command

### Base snippets

It helps you to create network device configuration

PREFIX - DESCRIPTION

-- GENERAL:
transceiver - Disable 3d party transceiver alarm

-- BASIC:
aaa - Create AAA
console - Configure console port
vty - Configure VTY interface
ssh user - Create new SSH user

-- ACL:
acl number - Create ACL

-- INTERFACE:
interface - Create new interface
ip address - Assign new IP and mask

-- VLAN:
vlan - Create new single VLAN
vlan batch - Create VLAN batch
port default vlan - Bind access port to VLAN
port trunk allow-pass vlan - Allow VLANs on trunk port

-- BFD:
discriminator - Assign BFD discriminator

-- VPN:
ip vpn-instance - Create new VPN instance
ip binding vpn-instance - Bind to VPN instance

-- VRRP:
vrrp vrid - Bind to new VRRP instance

-- STATIC ROUTING:
ip route-static - Create global static IP route
ip route-static vpn-instance - Create VPN static IP route
