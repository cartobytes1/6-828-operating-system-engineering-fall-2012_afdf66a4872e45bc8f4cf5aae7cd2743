---
course_id: 6-828-operating-system-engineering-fall-2012
layout: course_section
menu:
  leftnav:
    identifier: 918acd06aca51088ed187978df900929
    name: Lecture Notes and Readings
    weight: 30
title: Lecture Notes and Readings
type: course
uid: 918acd06aca51088ed187978df900929

---

Some of the readings require the [xv6 code (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_xv6-sourc-rev7), as well as the [xv6 book (PDF - 1.3MB)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_xv6-book-rev7), which are provided courtesy of Frans Kaashoek, Robert Morris, and Russ Cox and are used here with permission.

| LEC # | LECTURE TOPICS AND NOTES | READINGS AND HANDOUTS |
| --- | --- | --- |
| 1 | [Operating Systems (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec1_notes) | "Chapter 0: Operating System Interfaces" of xv6 book |
| 2 | [PC Hardware and x86 Programming (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec2_notes) | "Appendix A: PC Hardware" and "Appendix B: The Boot Loader" of xv6 book, and the related xv6 source files |
| 3 | [Overview of Major Internals, System Call Interface (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec3_notes) | "Chapter 1: The first process" and the related xv6 source files |
| 4 | [Virtual Memory (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec4_notes) |  {{< br >}}{{< br >}} "Chapter 2: Page Tables" {{< br >}}{{< br >}} [Page Table Translation and Registers (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec4_handout) {{< br >}}{{< br >}}  |
| 5 | [Interrupts, Exceptions (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec5_notes) |  {{< br >}}{{< br >}} "Chapter 3: Traps, interrupts, and drivers" and the related xv6 source files {{< br >}}{{< br >}} [IDT (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec5_handout) {{< br >}}{{< br >}}  |
| 6 | [Multiprocessors and Locking (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec6_notes) | "Chapter 4: Locking" with spinlock.c and skim mp.c |
| 7 | [Processes and Switching (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec7_notes) | "Chapter 5: Scheduling" up to "Sleep and wakeup" with proc.c, setjmp.S, and sys\_fork (in sysproc.c) |
| 8 | [Sleep & Wakeup (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec8_notes) | Read remainder of "Chapter 5: Scheduling"; read remainder of proc.c and sys\_wait, sys\_exit, sys\_kill |
| 9 | [File Systems (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec9_notes) | "Chapter 6: File system" and bio.c, fs.c, sysfile.c, file.c, except for the logging sections |
| 10 | [Crash Recovery (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec10_notes) | Read log.c and the logging sections of "Chapter 6: File system" |
| 11 | [File System Performance and Fast Crash Recovery (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec11_notes) | Tweedie, Stephen C. "[Journaling the Linux ext2fs Filesystem](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.307.9137)." \[Paper Presented at LinuxExpo 1998\]. |
| 12 | Project Introduction and Discussion | &nbsp; |
| 13 | [OS Organization (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec13_notes) | Engler, Dawson R., M. Frans Kaashoek, and James O'Toole Jr. "[Exokernel: An Operating System Architecture for Application-Level Resource Management](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.52.2893)." |
| 14 | In-class Hacking Session | &nbsp; |
| 15 | Project Conferences | &nbsp; |
| 16 | Project Conferences (cont.) | &nbsp; |
| 17 | [Language / OS Co-design (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec17_notes) | Hunt, Galen C., and James R. Larus. "[Singularity: Rethinking the Software Stack](http://dx.doi.org/10.1145/1243418.1243424)." _Microsoft Research Redmond_ 41, no. 2 (2007): 37–49. |
| Quiz | Quiz (Open Book and Notes) | &nbsp; |
| 18 | [Scalable Locks (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec18_notes) | Boyd-Wickizer, Silas, M. Frans Kaashoek, et al. "[Non-Scalable Locks are Dangerous](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.261.196)." |
| 19 | Project Conferences | &nbsp; |
| 20 | Project Conferences (cont.) | Boyd-Wickizer, Silas, Austin T. Clements, et al. "[An Analysis of Linux Scalability to Many Cores](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.174.5191)." |
| 21 | [Lock-free Coordination (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec21_notes) | &nbsp; |
| 22 | [Virtual Machines (PDF)]({{< baseurl >}}/sections/lecture-notes-and-readings/mit6_828f12_lec22_notes) | Adams, Keith, and Ole Agesen. "[A Comparison of Software and Hardware Techniques for x86 Virtualization](http://dx.doi.org/10.1145/1168857.1168860)." _ACM Digital Library_ 34, no. 5 (2006): 2–13. |
| 23 | No lecture; work on final projects | &nbsp; |
| 24 | Demos in class | &nbsp; |
| 25 | Demos in class (cont.) |