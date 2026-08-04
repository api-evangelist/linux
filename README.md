# Linux (linux)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
