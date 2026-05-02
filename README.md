# Linux (linux)
Linux is an open-source Unix-like operating system kernel originally created by Linus Torvalds. This index catalogs the userspace and kernel programming interfaces exposed by Linux, including system calls, eBPF, ioctl, netlink, procfs, sysfs, GPIO, and security interfaces such as Seccomp, Landlock, and Linux Security Modules. It also covers ecosystem APIs for systemd and PAM.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/linux/refs/heads/main/apis.yml)

## Scope
- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:
 - Kernel, Linux, Open Source, Operating System, Unix, Userspace API

## Timestamps
- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### Linux Kernel Userspace API
The set of stable userspace-facing interfaces exposed by the Linux kernel, including system calls, ioctls, eBPF, futex2, and the netlink protocol.

**Human URL:** [https://www.kernel.org/doc/html/latest/userspace-api/index.html](https://www.kernel.org/doc/html/latest/userspace-api/index.html)

#### Tags:
 - Kernel, Userspace, System Calls

#### Properties
- [Documentation](https://www.kernel.org/doc/html/latest/userspace-api/index.html)
- [Reference](https://man7.org/linux/man-pages/man2/syscalls.2.html)

### eBPF Userspace API
Extended Berkeley Packet Filter (eBPF) userspace API for loading and interacting with sandboxed programs running in the kernel.

**Human URL:** [https://www.kernel.org/doc/html/latest/userspace-api/ebpf/index.html](https://www.kernel.org/doc/html/latest/userspace-api/ebpf/index.html)

#### Tags:
 - eBPF, Kernel, Observability

#### Properties
- [Documentation](https://www.kernel.org/doc/html/latest/userspace-api/ebpf/index.html)

### Netlink API
Socket-based interface for communication between the kernel and userspace, used widely for networking, routing, and device configuration.

**Human URL:** [https://man7.org/linux/man-pages/man7/netlink.7.html](https://man7.org/linux/man-pages/man7/netlink.7.html)

#### Tags:
 - Networking, IPC, Kernel

#### Properties
- [Documentation](https://www.kernel.org/doc/html/latest/userspace-api/netlink/index.html)

### Seccomp BPF
SECure COMPuting mode with BPF filters, used to restrict which system calls a process can make for sandboxing and hardening.

**Human URL:** [https://www.kernel.org/doc/html/latest/userspace-api/seccomp_filter.html](https://www.kernel.org/doc/html/latest/userspace-api/seccomp_filter.html)

#### Tags:
 - Security, Sandboxing, Syscalls

#### Properties
- [Documentation](https://www.kernel.org/doc/html/latest/userspace-api/seccomp_filter.html)

### Landlock
Unprivileged access-control framework allowing processes to restrict themselves and their descendants from filesystem and network operations.

**Human URL:** [https://www.kernel.org/doc/html/latest/userspace-api/landlock.html](https://www.kernel.org/doc/html/latest/userspace-api/landlock.html)

#### Tags:
 - Security, Access Control

#### Properties
- [Documentation](https://www.kernel.org/doc/html/latest/userspace-api/landlock.html)

### procfs
Virtual filesystem mounted at /proc that exposes process and kernel information through a file-based interface.

**Human URL:** [https://man7.org/linux/man-pages/man5/proc.5.html](https://man7.org/linux/man-pages/man5/proc.5.html)

#### Tags:
 - Filesystem, Process, Monitoring

#### Properties
- [Documentation](https://www.kernel.org/doc/html/latest/filesystems/proc.html)

### sysfs
Virtual filesystem mounted at /sys that exports kernel object and device information to userspace.

**Human URL:** [https://man7.org/linux/man-pages/man5/sysfs.5.html](https://man7.org/linux/man-pages/man5/sysfs.5.html)

#### Tags:
 - Filesystem, Devices, Kernel

#### Properties
- [Documentation](https://www.kernel.org/doc/html/latest/filesystems/sysfs.html)

### systemd D-Bus API
The system and service manager API exposed by systemd over D-Bus for managing units, services, and the boot process.

**Human URL:** [https://www.freedesktop.org/wiki/Software/systemd/dbus/](https://www.freedesktop.org/wiki/Software/systemd/dbus/)

#### Tags:
 - systemd, D-Bus, Service Management

#### Properties
- [Documentation](https://www.freedesktop.org/software/systemd/man/)
- [Reference](https://www.freedesktop.org/wiki/Software/systemd/dbus/)

### Linux PAM
Pluggable Authentication Modules providing flexible, configurable authentication mechanisms for Linux applications.

**Human URL:** [http://www.linux-pam.org/](http://www.linux-pam.org/)

#### Tags:
 - Authentication, Security

#### Properties
- [Documentation](http://www.linux-pam.org/Linux-PAM-html/)

### udev
Device manager for the Linux kernel handling device nodes and hotplug events under /dev.

**Human URL:** [https://www.freedesktop.org/software/systemd/man/udev.html](https://www.freedesktop.org/software/systemd/man/udev.html)

#### Tags:
 - Devices, Hardware, Hotplug

#### Properties
- [Documentation](https://www.freedesktop.org/software/systemd/man/udev.html)

## Common Properties
- [Kernel.org](https://www.kernel.org/)
- [Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/)
- [Linux man-pages](https://man7.org/linux/man-pages/)
- [Linux Foundation](https://www.linuxfoundation.org/)

## Maintainers
**FN:** Kin Lane
**Email:** kin@apievangelist.com
