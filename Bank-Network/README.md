CASE STUDY.
* CHUJA Company Ltd. is a UK-owned company that deals with Banking and Insurance. The company is intending to expand its services across the African continent having the first branch to be located in Nairobi, Kenya. The company has secured a four-story building to operate within the Kenyan capital city. Therefore, the company would like to source the knowledge from a group of final-year students from a local university to design and implement their company network.
* Assume you are among the students to take over this role, carefully read down the requirements then model the design and implement the network based on the company's needs. Each floor has departments as provided in the table below;
    1. First Floor
        Management - 20 PCs & 4 Printers.
        Research - 20 PCs & 4 Printers.
        HR - 20 PCs & 4 Printers.

    2. Second Floor
        Marketing - 20 PCs & 4 Printers.
        Accounting - 20 PCs & 4 Printers.
        Finance - 20 PCs & 4 Printers.

    3. Third floor
        Logistics/Store - 20 PCs & 4 Printers.
        Customer Care - 20 PCs & 4 Printers.
        Guest Area - 40 PCs & 2 Printers.

    4. Fourth Floor
        Admin - 20 PCs & 2 Printers.
        IT - 20 PCs & 2 Printers.
        Server Room - 2 PCs & 3 Servers (Web, Mail, DHCP)

    * Use any of the following network simulation software to implement the above topology.
    - Simulation software: Cisco Packet tracer or GNS3 for design and implementation.
    * Use OSPF as the routing protocol to advertise routes.
    * Each department is required to have a wireless network for the users.
    * Each department is excepted by the server room to have around 60 users both wired and wireless users.
    * Host devices in the network are required to obtain IPv4 addresses automatically from the dedicated DHCP server located at the server room.
    * Devices in all the departments are required to communicate with each other.
    * Create HTTP, and E-mail servers.
    * Configure SSH in all the routers for remote login.
    * Configure the basic configuration of the devices: 
        * Hostnames
        * Line Console
        * Enable passwords
        * Banner messages 
        * Disable domain IP lookup
        * encrypt all configured passwords.
    * Each department should be in a different VLAN and subnetwork; VLANs you will use in your case, e.g. 10, 20, 30… etc..
    * Planning of IP Addresses: You have been given 192.168.10.0 as the base address for this network. Do subnetting based on the number of hosts in every department as provided above. Identify subnet mask, useable IP address range, and broadcast address for each subnet.
    * End Device Configurations: Configure all the end devices in the network with the appropriate IP address based on the calculations above.
    * Configure port-security: Use sticky command to obtain MAC Address and Violation mode of the shutdown.
    * Test and Verifying Network Communication.

Technologies to be Implemented.

    * Creating a network topology using Cisco Packet Tracer.
    * Hierarchical Network Design.
    * Connecting Networking devices with Correct cabling.
    * Configuring Basic device settings.
    * Creating VLANs and assigning ports VLAN numbers.
    * Subnetting and IP Addressing.
    * Configuring Inter-VLAN Routing on the Multilayer switches (Switch Virtual Interface).
    * Configuring Dedicated DHCP Server device to provide dynamic IP allocation.
    * Configuring SSH for secure Remote access.
    * Configuring OSPF as the routing protocol.
    * Configuring switchport security or Port-Security on the switches.
    * Configuring WLAN or wireless network (Cisco Access Point).
    * Host Device Configurations.
    * Test and Verifying Network Communication.
