# advisories
[![](https://img.shields.io/github/stars/0xdea/advisories.svg?style=flat&color=yellow)](https://github.com/0xdea/advisories)
[![](https://img.shields.io/github/forks/0xdea/advisories.svg?style=flat&color=green)](https://github.com/0xdea/advisories)
[![](https://img.shields.io/github/watchers/0xdea/advisories.svg?style=flat&color=red)](https://github.com/0xdea/advisories)
[![](https://img.shields.io/badge/twitter-%400xdea-blue.svg)](https://twitter.com/0xdea)
[![](https://img.shields.io/badge/mastodon-%40raptor-purple.svg)](https://infosec.exchange/@raptor)

> "Testing can prove the presence of bugs, but not their absence." 
>
> -- Edsger W. Dijkstra

## Linux
* [**CVE-2006-1242**](https://www.securityfocus.com/archive/1/427622/100/0/threaded). Linux kernel IP ID information disclosure weakness.

## OpenSSH
* [**2003-01-openssh**](https://github.com/0xdea/advisories/blob/master/2003-01-openssh.txt). OpenSSH/PAM delay information disclosure vulnerability (CVE-2003-0190).
* [**CVE-2006-5229**](https://www.securityfocus.com/archive/1/448025/100/0/threaded). OpenSSH information disclosure via timing leak.

## X.Org
* [**CVE-2022-46285**](https://lists.x.org/archives/xorg-announce/2023-January/003312.html). Infinite loop on unclosed comments handling XPM files in libXpm.

## Azure
* [**CVE-2024-25110**](https://github.com/Azure/azure-uamqp-c/security/advisories/GHSA-c646-4whf-r67v). Integer wraparound vulnerability in Azure IoT Platform Device SDK.
* [**CVE-2024-29195**](https://github.com/Azure/azure-c-shared-utility/security/advisories/GHSA-m8wp-hc7w-x4xg). Integer wraparound vulnerability in Azure C SDK.

## Solaris
* [**2019-01-cde-dtprintinfo**](https://github.com/0xdea/advisories/blob/master/2019-01-cde-dtprintinfo.txt). Local privilege escalation via CDE dtprintinfo (CVE-2019-2832).
* [**2019-02-solaris-xscreensaver**](https://github.com/0xdea/advisories/blob/master/2019-02-solaris-xscreensaver.txt). Local privilege escalation via xscreensaver (CVE-2019-3010).
* [**2020-01-solaris-xlock**](https://github.com/0xdea/advisories/blob/master/2020-01-solaris-xlock.txt). Low impact information disclosure via Solaris xlock (CVE-2020-2656).
* [**2020-02-cde-dtsession**](https://github.com/0xdea/advisories/blob/master/2020-02-cde-dtsession.txt). Local privilege escalation via CDE dtsession (CVE-2020-2696).
* [**2020-05-cde-sdtcm_convert**](https://github.com/0xdea/advisories/blob/master/2020-05-cde-sdtcm_convert.txt). Local privilege escalation via CDE sdtcm_convert (CVE-2020-2944).
* [**2020-06-cde-libDtSvc**](https://github.com/0xdea/advisories/blob/master/2020-06-cde-libDtSvc.txt). Stack-based buffer overflow in CDE libDtSvc (CVE-2020-2851).
* [**2020-07-solaris-whodo-w**](https://github.com/0xdea/advisories/blob/master/2020-07-solaris-whodo-w.txt). Heap-based buffer overflow in Solaris whodo, w commands (CVE-2020-2771).
* [**HNS-2022-01-dtprintinfo**](https://github.com/0xdea/advisories/blob/master/HNS-2022-01-dtprintinfo.txt). Multiple vulnerabilities in Solaris dtprintinfo and libXm/libXpm (CVE-2022-46285, CVE-2023-24039, CVE-2023-24040).

## Zyxel
* [**HNS-2022-02-zyxel-zysh**](https://github.com/0xdea/advisories/blob/master/HNS-2022-02-zyxel-zysh.txt). Multiple vulnerabilities in Zyxel zysh (CVE-2022-26531, CVE-2022-26532).
* **CVE-2025-1732**. *TBA*.
* **CVE-2025-XXXX**. *TBA*.

## Zephyr
* [**HNS-2023-03-zephyr**](https://github.com/0xdea/advisories/blob/master/HNS-2023-03-zephyr.txt). Multiple vulnerabilities in Zephyr RTOS (CVE-2023-3725, CVE-2023-4257, CVE-2023-4259, CVE-2023-4260, CVE-2023-4261, CVE-2023-4262, CVE-2023-4263, CVE-2023-4264, CVE-2023-4265, CVE-2023-5139, CVE-2023-5184, CVE-2023-5753).

## RT-Thread
* [**HNS-2024-05-rt-thread**](https://github.com/0xdea/advisories/blob/master/HNS-2024-05-rt-thread.txt). Multiple vulnerabilities in RT-Thread RTOS (CVE-2024-24334, CVE-2024-24335, CVE-2024-25388, CVE-2024-25389, CVE-2024-25390, CVE-2024-25391, CVE-2024-25392, CVE-2024-25393, CVE-2024-25394, CVE-2024-25395).

## ThreadX
* [**HNS-2024-06-threadx**](https://github.com/0xdea/advisories/blob/master/HNS-2024-06-threadx.txt). Multiple vulnerabilities in Eclipse ThreadX (CVE-2024-2212, CVE-2024-2214, CVE-2024-2452).

## RIOT
* [**HNS-2024-07-riot**](https://github.com/0xdea/advisories/blob/master/HNS-2024-07-riot.txt). Multiple vulnerabilities in RIOT OS (CVE-2024-31225, CVE-2024-32017, CVE-2024-32018).

## Others
* [**smbfs/umount**](https://www.illumos.org/issues/11618). Buffer overflow in Illumos smbfs/umount.
* [**dhclient**](https://gitlab.isc.org/isc-projects/dhcp/-/issues/280). Format string bug in ISC DHCP configuration file handling.
* [**coturn**](https://github.com/coturn/coturn/pulls?q=is%3Apr+0xdea). Security issues in the Coturn TURN server.
* [**FreeRTOS-Plus-TCP**](https://github.com/FreeRTOS/FreeRTOS-Plus-TCP/pull/1017). Security issues in FreeRTOS (uncredited).
* [**lwIP/httpclient**](https://git.savannah.nongnu.org/cgit/lwip.git/commit/?id=ee1523630a81fffa6b7d93dd0c7a6191de5856cd). Integer wraparound and heap buffer overflow in lwIP (uncredited).
* [**lwIP/makefsdata**](https://git.savannah.nongnu.org/cgit/lwip.git/commit/?id=b413b040936f48d4cd9ed632ac579542c710efae). Integer underflow and static buffer overflow (uncredited).
* [**HNS-2023-04-tinydir**](https://github.com/0xdea/advisories/blob/master/HNS-2023-04-tinydir.txt). Buffer overflow vulnerabilities with long path names in TinyDir (CVE-2023-49287).
