# LibKernel
A collection of libraries which would interact with kernel

# Libraries
libnftnl (Netfilter nftables API library):
Purpose: This library is used to interface with the Netfilter subsystem in the Linux kernel, specifically for nftables, which is the successor to iptables. nftables provides a framework for packet filtering, network address translation (NAT), and other packet manipulation.
Kernel Interaction: It interacts with the kernel by sending commands to and receiving responses from the nftables kernel component. This allows for the creation, modification, and deletion of firewall rules directly in the kernel.
libbpf (BPF Library):
Purpose: libbpf is a library for working with the BPF (Berkeley Packet Filter), particularly the extended BPF (eBPF) which is a more powerful version used for various purposes like performance monitoring, networking, and security.
Kernel Interaction: It provides an interface for loading BPF programs into the kernel, manipulating BPF maps (key-value data structures for communication between user space and BPF programs), and other eBPF-related functionalities. These programs run in the kernel space, allowing for high-performance data processing and monitoring.
libudev (udev Library):
Purpose: Part of systemd, libudev provides an interface for interacting with the udev device manager, responsible for managing device nodes in the /dev directory.
Kernel Interaction: It allows applications to communicate with the udev daemon to receive notifications about device events (like addition or removal of devices) from the kernel, query device information, and interact with the device filesystem dynamically managed by the kernel.
libpcap (Packet Capture Library):
Purpose: libpcap is used for network traffic capture. It's the library behind tools like Tcpdump and Wireshark and is commonly used for network diagnostics and packet analysis.
Kernel Interaction: It interfaces with the network stack of the kernel to capture packets. The library abstracts the details of different operating system packet capture mechanisms, providing a unified interface for capturing network traffic.
libusb (USB Library):
Purpose: This library allows applications to access and communicate with USB devices across different operating systems.
Kernel Interaction: It interacts with the USB subsystem in the kernel, providing an API for applications to perform operations like enumerating USB devices, transferring data, and managing USB configurations.
libdrm (Direct Rendering Manager Library):
Purpose: This library is part of the Linux graphics stack, used for interfacing with the Direct Rendering Manager (DRM) in the Linux kernel. DRM is a component that manages access to graphics cards and provides an API for direct rendering.
Kernel Interaction: libdrm communicates with GPU kernel drivers, enabling applications to use GPU resources for rendering tasks. It's essential for implementing high-performance graphics applications and is used by various windowing systems and graphics frameworks.
