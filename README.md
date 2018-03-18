# hardened-gentoo-hardened

## Description

hardened-gentoo-hardened is an attempt to formalise the creation of a reasonably secure Gentoo Linux installation, extending beyond the normal (hardened) Gentoo Linux setup, including some degree of containerisation and application isolation. 

## TO DO
- [ ] Basic installation details
- [ ] SELinux MCS/MLS installation
- [ ] ZFS
- [ ] Authentication and roles
- [ ] Auditing
- [ ] Integrity checks
- [ ] Monitoring
- [ ] Reporting
- [ ] Containerisation
- [ ] Logging
- [ ] Network Firewall (security labels and packet filtering)
- [ ] Raspberry PI basic setup
- [ ] PKI management 
- [ ] Password management
- [ ] Signing

### Goals

The main goal of this document is to organise my attempts to create a reasonably secure Linux installation in a readable format. 

### Non-goals

Creating a comprehensive tutorial covering all aspects of security is definitely not a goal. Attaining certifiable or military-grade security is also not a goal and everything documented here should be taken with care. 

### Design principles

#### Isolation
Services running on the server should be exposed as little as possible or not exposed at all when it's not necessary.

#### Mandatory access control

#### Performance

#### Simplicity

## Requirements

* A Linux-compatible computer that will host the main server
* (Optional) a number of additional nodes for redundancy, storage and backups
* (Optional) a barebone PC (eg. a Rapsberry Pi) for isolated key management. 

## Service installation and configuration

### Auditing

### Email (SMTP)

### Email (IMAP)

### PostgreSQL

### DNS

### Integrity

### Monitoring

### Logging

### VPN

### Proxying

## Missing pieces

Centralised orchestration and administration

## (In)frequently Asked Questions

### Why?

Installing and configuring a Linux installation (especially a Gentoo Linux) is a cumbersome and time-consuming task. Documentation and tutorials are scattered throughout the Internet and many contain only fragments of useful information, so I wanted to have a collection of practices that may help building a secure server box in a reproducible manner.

## References

[1] [Gentoo installation handbook](https://wiki.gentoo.org/wiki/Handbook:AMD64)
[2] [Gentoo SELinux handbook](https://wiki.gentoo.org/wiki/SELinux/Installation)
[3] [Limitations of air gapping](https://en.wikipedia.org/wiki/Air_gap_%28networking%29#Limitations)
[4] [Mail Server Guide](https://www.c0ffee.net/blog/mail-server-guide)
[5] [Linux IP networks](http://linux-ip.net/html/index.html)
[6] [Gentoo Kernel module signing](https://wiki.gentoo.org/wiki/Signed_kernel_module_support)
[7] [DNSSEC with Unbound](https://unbound.net/documentation/howto_anchor.html)
[8] [iptables with SELinux](https://www.linux.com/learn/using-selinux-and-iptables-together)
[9] [Generating SECMARK rules](https://fedorapeople.org/~dwalsh/SELinux/secmark/secmarkgen)
[10] [Authentication management](https://www.privacyidea.org/)
[11] [Audit record types](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/security_guide/sec-audit_record_types)
