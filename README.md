# LibKernel
A collection of libraries which would interact with kernel

# Libraries
## libnftnl (Netfilter nftables API library)
- **Purpose**: Interface with the Netfilter subsystem for nftables.
- **Kernel Interaction**: Manipulate firewall and network packet filtering rules.

## libbpf (BPF Library)
- **Purpose**: Work with BPF for networking, security, and performance monitoring.
- **Kernel Interaction**: Load BPF programs into the kernel and manipulate BPF maps.

## libudev (udev Library)
- **Purpose**: Interact with the udev device manager.
- **Kernel Interaction**: Communicate with the udev daemon for device events.

## libpcap (Packet Capture Library)
- **Purpose**: Capture network traffic.
- **Kernel Interaction**: Interface with the network stack for packet capture.

## libusb (USB Library)
- **Purpose**: Access and communicate with USB devices.
- **Kernel Interaction**: Interface with the USB subsystem.

## libdrm (Direct Rendering Manager Library)
- **Purpose**: Interface with the GPU kernel drivers.
- **Kernel Interaction**: Manage access to graphics cards and perform rendering tasks.

## libc (Standard C Library)
- **Purpose**: Fundamental operations like file I/O, process control, and memory management.
- **Kernel Interaction**: System call interface connecting to the kernel.

## libaio (Linux-native Asynchronous I/O Library)
- **Purpose**: Perform non-blocking I/O operations.
- **Kernel Interaction**: Interact with the kernel's AIO subsystem.

## libcap (POSIX Capabilities Library)
- **Purpose**: Control and query process capabilities.
- **Kernel Interaction**: Manipulate and inspect capabilities of processes and files.

## libm (Math Library)
- **Purpose**: Provide mathematical functions.
- **Kernel Interaction**: Some functions may interact with the kernel for hardware-accelerated operations.

## libseccomp (Secure Computing Mode Library)
- **Purpose**: Limit process system calls.
- **Kernel Interaction**: Restrict a process's ability to make system calls.

## libkmod (Kernel Module Library)
- **Purpose**: Handle Linux kernel modules.
- **Kernel Interaction**: Load, unload, and manage kernel modules.
