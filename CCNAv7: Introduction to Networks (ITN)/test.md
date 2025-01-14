
1.5.7/1.5.5 Packet Tracer – Network Representation (Instruction Answers)
Oct 23, 2019 Last Updated: May 14, 2023 CCNA 1 Labs - Packet Tracer, CCNA v7 Course #1, CCNA v7.0 3 Comments
Share
Tweet
Share
Pin it
1.5.5 Packet Tracer – Network Representation (Instructor Version – Optional Packet Tracer)
# 1.5.7 Packet Tracer – Network Representation

Instructor Note: Red font color or green highlights indicate text that appears in the instructor copy only.

All clients have full connectivity to the servers. For the sake of frame diversity, the environment is not entirely realistic. For instance:

    NAT and PAT overload are both used on the Branch network, but the Central 10.X.X.X network is shared publicly.
    There is a separate DNS server in the 172 network because the computers cannot use the filer server’s public address. The simulated DNS server, unlike BIND, is basic and does not forward requests that it does not know to a root server. Therefore, the A records are duplicated.
    EIGRP is running in the cloud, instead of BGP.
    The Branch switch is providing DHCP, just because it can. It makes that side of the simulation different than the Central side.
    The cloud includes two servers. One server uses the correct IP (netacad.com). The other server uses the correct IP of Google’s DNS.
    The router passwords are “cisco” and “class”, but there is a “banner motd” and “banner login” which readily provide the passwords.
    The S1 and S2 switches have spanning tree PVST enabled. Each has a different blocking port, so all connections are green.

Topology
1.5.7 Packet Tracer - Network Representation

# 1.5.7 Packet Tracer – Network Representation
Objectives

The network model in this activity incorporates many of the technologies that you will master in your CCNA studies. It represents a simplified version of how a small to medium-sized business network might look. Feel free to explore the network on your own. When you are ready, proceed through the following steps and answer the questions.

Note: It is not important that you understand everything you see and do in this activity. Feel free to explore the network on your own. If you wish to proceed more systematically, follow the steps below. Answer the questions to the best of your ability.

## Step 1: Identify common components of a network as represented in Packet Tracer.

-   a. The icon toolbar at the bottom left hand corner has various categories of networking components. You should see categories that correspond to intermediary devices, end devices, and media. The Connections category (with the lightning bolt icon) represents the networking media supported by Packet Tracer. There is also an End Devices category and two categories specific to Packet Tracer: Custom Made Devices and Multiuser Connection.
-  b. List the intermediary device categories.

            Routers, Switches, Hubs, Wireless Devices, and WAN Emulation

-  c. Without entering into the Internet cloud or Intranet cloud, how many icons in the topology represent endpoint devices (only one connection leading to them)?

            15

-  d. Without counting the two clouds, how many icons in the topology represent intermediary devices (multiple connections leading to them)?

            11

-  e. How many end devices are not desktop computers?

            8

-  f. How many different types of media connections are used in this network topology?

            4

## Step 2: Explain the purpose of the devices.

    a. In Packet Tracer, only the Server-PT device can act as a server. Desktop or Laptop PCs cannot act as a server. Based on your studies so far, explain the client-server model.

>    In modern networks, a host can act as a client, a server, or both. Software installed on the host determines the role it plays on the network. Servers are hosts that have software installed that enables them to provide information and services, like email or web pages, to other hosts on the network. Clients are hosts that have software installed that enables them to request and display the information obtained from the server. A client could also be configured as a server simply by installing server software.
    b. List at least two functions of intermediary devices.

    Regenerate and retransmit data signals; maintain information about what pathways exist through the network and internetwork; notify other devices of errors and communication failures; Direct data along alternate pathways when there is a link failure; Classify and direct messages according to QoS priorities; Permit or deny the flow of data, based on security settings.
    c. List at least two criteria for choosing a network media type.

    The distance the media can successfully carry a signal. The environment in which the media is to be installed. The amount of data and the speed at which it must be transmitted. The cost of the media and installation.

Step 3: Compare and contrast LANs and WANs.

        a. Explain the difference between a LAN and a WAN. Give examples of each.

LANs provide access to end users in a small geographical area. A home office or school campus are examples of LANs. WANs provide access to users in a wide geographical area over long distances spanning a few miles to thousands of miles. A Metropolitan Area Network and the Internet are examples of WANs. A company’s intranet may also connect multiple remote sites using a WAN.

        b. In the Packet Tracer network, how many WANs do you see? There are two: the Internet and the Intranet WANs.
        c. How many LANs do you see?

There are three, easily identifiable because each has a border and label.

        d. The Internet in this Packet Tracer network is overly simplified and does not represent the structure and form of the real Internet. Briefly describe the Internet.

The Internet is mostly used when we need to communicate with a resource on another network. The Internet is a global mesh of interconnected networks (internetworks).

        e. What are some of the common ways a home user connects to the Internet?

Cable, DSL, dial-up, cellular, and satellite.

        f. What are some common methods that businesses use to connect to the Internet in your area?

Dedicated leased line, Metro-E, DSL, Cable, Satellite
Challenge

Now that you have had an opportunity to explore the network represented in 1.5.7 Packet Tracer – Network Representation activity, you may have picked up a few skills that you would like to try out. Or maybe you would like the opportunity to explore this network in more detail. Realizing that most of what you see and experience in Packet Tracer is currently beyond your skill level, here are some challenges you might want to attempt. Do not worry if you cannot do them all. You will be a Packet Tracer master user and network designer soon enough.

    Add an end device to the topology and connect it to one of the LANs with a media connection. What else does this device need to send data to other end users? Can you provide the information? Is there a way to verify that you correctly connected the device?
    Add a new intermediary device to one of the networks and connect it to one of the LANs or WANs with a media connection. What else does this device need to serve as an intermediary to other devices in the network?
    Open a new instance of Packet Tracer. Create a new network with at least two LANs connected by a WAN. Connect all the devices. Investigate the original Packet Tracer activity to see what else you might need to do to make your new network functional. Record your thoughts and save your Packet Tracer file. You may want to revisit your network later after you have mastered a few more skills.
