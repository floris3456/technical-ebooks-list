# Cycle 2026-10-16-01 — exact source audit

**Source access date: 2026-10-16, Europe/Amsterdam** for every new opening, not the publication/revision date. Starting pinned main `60251a7b1cc3ebadadaf3011da3af82eb81a5789`. Read README, TAXONOMY, BOOK_TEMPLATE, STATE, existing source/retention/correction indexes, latest source-only commit, 28-work catalog, the CSAPP3e pending record, Security Engineering 3e, and observable cycle-06 research WIP. No unavailable prior run history was inferred. Current cycle deliberately investigated Kerrisk's Linux system-programming textbook instead of duplicating cycle-06 work on Rust 3e. Source attempts were checkpointed immediately after each retrieval batch; some GitHub write requests failed safety checks and were retried via non-force commits. The final tree retains source records.

## New website families, conservatively scoped

**23 newly opened website families** compared with all registered historical sites (including failed visits); **21 substantively examined under conservative grouping** after withholding BusyBox's thin overview and the Firecracker GitHub Pages site as potentially a known GitHub-hosting ecosystem. All substantive primary vendor/framework sites below are **technology context, not endorsements of the 2010 book**. Count websites, not pages or subdomains.

| Family | Exact representative directly opened URL | What was read; document date (if established) |
| --- | --- | --- |
| 01 wm.edu | https://www.cs.wm.edu/~smherwig/courses/csci415-f2026/index.html | **Fall 2026** original chapter-level reading and projects; independent university adoption |
| 02 tum.de | https://dse.in.tum.de/advanced-systems-programing-sose2021/ | **Summer 2021** advanced C/Rust systems course and Kerrisk reading |
| 03 slashdot.org | https://books.slashdot.org/story/10/11/08/1430238/The-Linux-Programming-Interface | Federico Lucifredi independent firsthand review; **2010-11-08** |
| 04 strace.io | https://strace.io/ | syscall tracing/filters and failure injection; original update unknown |
| 05 libevent.org | https://libevent.org/ | callback/epoll event-loop abstractions; releases include **2026-07-01**, footer update differs |
| 06 landlock.io | https://landlock.io/ | unprivileged LSM filesystem restrictions; revision unknown |
| 07 libuv.org | https://docs.libuv.org/en/v1.x/guide/basics.html | actual event-loop guide and error handlers; revision unknown; first homepage was thin |
| 08 unixism.net | https://unixism.net/loti/what_is_io_uring.html | shared io_uring SQ/CQ example, **2020**, not present-day performance claims |
| 09 ebpf.io | https://ebpf.io/what-is-ebpf/ | probes, verifier and eBPF maps; update unknown |
| 10 rr-project.org | https://rr-project.org/ | syscall deterministic replay/reverse debugging; update unknown |
| 11 curl.se | https://curl.se/libcurl/c/libcurl.html | libcurl easy/multi interfaces; current reference, update unknown |
| 12 boost.org | https://www.boost.org/doc/libs/latest/doc/html/boost_asio.html | Asio async networking overview; page copyright through 2026, exact update unknown |
| 13 debian.org | https://manpages.debian.org/unstable/manpages-dev/open.2.en.html | O_CLOEXEC, openat2, O_TMPFILE; rolling manual date unknown |
| 14 depaul.edu | https://dice.cs.depaul.edu/courses/882/index.html | **2022–23** Linux systems course exact TLPI reading |
| 15 systemd.io | https://systemd.io/ | PID1, service activation and cgroups; update unknown |
| 16 busybox.net | https://www.busybox.net/about.html | project scope only; **withheld conservative substantive credit** |
| 17 podman.io | https://docs.podman.io/en/latest/markdown/podman-run.1.html | container run options, namespaces; update unknown |
| 18 docker.com | https://docs.docker.com/engine/security/seccomp/ | seccomp default-profile scope; update unknown |
| 19 gvisor.dev | https://gvisor.dev/docs/architecture_guide/security/ | userspace interception as extra syscall isolation; update unknown |
| 20 linuxcontainers.org | https://linuxcontainers.org/lxc/introduction/ | namespaces, seccomp/cgroups, LTS 5.0/6.0 windows; update unknown |
| 21 firecracker-microvm.github.io | https://firecracker-microvm.github.io/ | KVM + jailer microVM isolation; **withheld independent-site credit** because GitHub hosting could overlap known ecosystem |
| 22 wireshark.org | https://www.wireshark.org/docs/wsug_html_chunked/ChapterIntroduction.html | §1.1 packet-capture/debugging roles and non-goals; date unknown |
| 23 haproxy.org | https://www.haproxy.org/download/3.0/doc/configuration.txt | HAProxy **3.0 manual dated 2026-10-14**, §1 modern TCP/HTTP2/3 behavior |

Known and returning No Starch samples, kerrisk/man7 author ecosystem, LWN 2011 review, kernel.org, Harvard/CMU, Cambridge, IEEE and other websites earn **zero** novel-site credit. New-family counts are independent of success/failure outcomes.

## Exactly logged incomplete attempts

- https://www.openssl.org/docs/manmaster/man7/ossl-guide-tls-client-block.html — tool inaccessible; no body read.
- https://bpftrace.org/docs/release_0.24.0 and https://liburing.io/ — internal errors; no body read.
- https://lttng.org/docs/v2.14/ — seven-line scraper shell; no technical evidence.
- https://www.openbsd.org/papers/pledge-unveil.pdf, https://www.netbsd.org/docs/guide/en/chap-processes.html, https://docs.illumos.org/books/dev/, https://www.freedesktop.org/software/systemd/man/latest/systemd.exec.html, https://selinuxproject.org/page/SELinux_Notebook, https://www.tcpdump.org/manpages/pcap.3pcap.html — failed openings; not substantive.
- https://www.openwall.com/lists/oss-security/ — general index only. https://docs.fedoraproject.org/en-US/quick-docs/selinux-getting-started/ — empty renderer shell. Both withheld credit.
- The broad initial discovery/search URL lists remain in `001-discovery.md` and `004-discovery-linux-uapi.md`; **snippets were never promoted to opened evidence**.

## Book evidence and review boundaries

Three actual official **first-edition sample chapter PDFs** (ch4 descriptor/copy code; ch24 fork/exec; ch52 POSIX mq lifecycle) were opened and selected pages rendered. Original reviewer [Jake Edge (2011-01-19)](https://lwn.net/Articles/423417/) and [Federico Lucifredi (2010-11-08)](https://books.slashdot.org/story/10/11/08/1430238/The-Linux-Programming-Interface) gave firsthand, qualified positive judgments. WM **Fall 2026** independently assigns explicit TLPI chapters. The author [printing-specific errata](https://kerrisk.com/tlpi/errata/errata_by_print_run.html) were last updated **2026-09-12**, not a new edition. Current Debian open(2) and kernel uAPI references illustrate real implementation changes without asserting complete code compatibility. Canonical [TLPI record](../../../books/kerrisk-linux-programming-interface-1.md) maps precise claims to URLs/pages.

Later-run CSAPP3e recheck used rendered [author cache-blocking aside](https://csapp.cs.cmu.edu/3e/waside/waside-blocking.pdf), [2025 author errata](https://csapp.cs.cmu.edu/3e/errata.html) and [Harvard 2026 instructor criticisms](https://cs61.seas.harvard.edu/site/2026/Textbook/). Older Security Engineering rotation reopened 3e [chapter1 §1.2](https://www.cl.cam.ac.uk/archive/rja14/Papers/SEv3-ch01.pdf) and [third-edition errata](https://www.cl.cam.ac.uk/archive/rja14/book/v3errata.html); an attempted independent IEEE review timed out, so it was not described as newly read. No full-book read, executed examples, all-printings errata audit or final collection audit was claimed.

## Chronological audit files

See numbered exact-source attempts **001–012**, including discovery-only, failures, and the original-chapter/source rechecks. Note: older attempts to update one longer source log were blocked, then its factual inspection summary was committed to `011-recheck.md`; omitted raw text must not be silently reconstructed.
