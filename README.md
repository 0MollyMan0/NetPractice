*This project has been created as part
of the 42 curriculum by anfouger*
# NetPractice

## Description

NetPractice is an introductory networking project from the 42 curriculum.

The goal of the project is to correctly configure small network topologies by assigning appropriate IP addresses, subnet masks, and routing information so that devices can communicate as expected. Each level presents a different scenario involving hosts, routers, and switches, with specific connectivity requirements to satisfy.

Rather than relying on code, NetPractice focuses on reasoning about how networks work: how IP addressing and subnetting determine reachability, how routers forward packets between networks, and how basic OSI layer concepts apply in real situations. The project is composed of multiple independent levels, each increasing in complexity and reinforcing key networking principles.

## Instructions

### Running the training interface

The NetPractice project is completed using a provided training interface. To launch it, run the following script from the project directory:

```bash
./run.sh
```

This will open the NetPractice interface in your browser or local environment, allowing you to work through the different networking levels interactively.

### Completing and exporting configurations

Each level requires you to correctly configure the network so that all required connections succeed. Once a level is validated in the interface, you must export the configuration using the export feature provided by NetPractice.

The export generates a configuration file corresponding to the completed level. These files are required for submission and serve as proof of completion.

### Submission requirements

For submission, you must provide:

- 10 exported configuration files, one for each level

- All files must be placed at the root of the Git repository

- No additional directories are required for the configuration files

Only the exported configuration files are evaluated. The project does not require compilation, binaries, or source code.

## Resources

This project is based on networking fundamentals acquired during my previous studies (BTS SIO) and reinforced through the following course:

* [Course on basics notions of networking - CiscoNetAcad](https://www.netacad.com/courses/networking-basics?courseLang=fr-FR&instance_id=f393c38f-b410-4d2b-8275-70e144273519)

### Networking Concepts Covered

During this project, I worked with and deepened my understanding of the following key networking concepts:

* **TCP/IP Addressing**<br>
  Understanding IPv4 addresses, their structure, and how hosts communicate within a network.

* **Subnet Masks**<br>
  Learning how to divide networks into subnets and determine network and host portions of an IP address.

* **CIDR (Classless Inter-Domain Routing)**<br>
  Efficient IP address allocation and subnetting using prefix notation (e.g., /24, /30).

* **Default Gateway**<br>
  Configuring and understanding how packets are routed outside a local network.

* **Routing**<br>
  Basic routing logic: how packets move between networks via routers.

* **Switching**<br>
  Role of switches in local networks (Layer 2) and how devices communicate within the same subnet.

* **OSI Model**<br>
  Understanding the different layers (especially Layer 2 – Data Link, Layer 3 – Network) and their responsibilities.

* **Network Topology & Connectivity**<br>
  Visualizing how devices are interconnected and ensuring proper communication paths.

* **IP Address Consistency & Validation**<br>
  Ensuring correct configuration to allow communication between all nodes in a network.

### Use of AI

AI was used only to assist in structuring and improving the clarity of this README. All networking concepts and problem-solving were done independently.