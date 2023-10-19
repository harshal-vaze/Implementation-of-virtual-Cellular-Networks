# Cellular-network-with-Open5gs-and-srsLTE

The project focused on the virtual implementation of a cellular network on a cloud platform, utilizing various software packages for the Core Network, Radio Access Network (RAN), and User Equipment (UE). Through the setup, the aim was to facilitate efficient control and data traffic exchange among the network functions.

![](topology.png)

Implementation Details:
The 4G (LTE) network was established using the Open5gs software for the core network and the srsLTE software for the RAN and UE components. Additionally, a standalone 5G (NR) network was created using the Open5gs software for the core network and the UERANSIM software for the RAN and UE. Control and User Plane Separation (CUPS) were integrated into the network configuration to enhance its performance.

Performance Testing and Enhancements:
To ensure optimal functionality, thorough throughput and bandwidth checks were conducted post-setup. The project also delved into the implementation of 5G network slicing, enabling the partitioning of the network into multiple virtual networks, each catering to specific services or requirements.

Incorporated Technologies:
The project further embraced Ansible-based automation to streamline and manage various network operations efficiently. Additionally, a comprehensive dashboard was developed, providing a centralized interface for monitoring and managing the network's performance, components, and resources.

Conclusion:
Through the virtual setup of cellular networks on a cloud platform, this project aimed to showcase the viability and efficacy of implementing advanced network functionalities, such as 5G slicing and automation, for optimized data and control traffic management.
