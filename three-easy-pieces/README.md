# Operating Systems: Three Easy Pieces

Offline chapters and code from the [official book website](https://pages.cs.wisc.edu/~remzi/OSTEP/). Downloaded 2026-10-27.

Read the numbered PDFs in order. Chapters 3–51 cover Virtualization, Concurrency, and Persistence, including their dialogues and summaries. Introductory material (chapters 1–2 and front matter), Security, and appendices are omitted.

## Code

- [Book examples](code/ostep-code/README.md): original folder names and shared headers are preserved. The introductory examples directory is omitted.
- [Homework simulators and exercises](code/ostep-homework/README.md): follow each directory’s instructions.

The downloaded code has not been built or run. Original upstream files, notices, and licenses are preserved for the included directories. Repository revisions, source URLs, and PDF checksums are recorded in [sources.json](sources.json).

## Virtualization

| Chapter | Reading |
| --- | --- |
| 3 | [Dialogue](01-virtualization/03-dialogue-virtualization.pdf) |
| 4 | [Processes](01-virtualization/04-cpu-intro.pdf) |
| 5 | [Process API](01-virtualization/05-cpu-api.pdf) |
| 6 | [Direct Execution](01-virtualization/06-cpu-mechanisms.pdf) |
| 7 | [CPU Scheduling](01-virtualization/07-cpu-sched.pdf) |
| 8 | [Multi-level Feedback](01-virtualization/08-cpu-sched-mlfq.pdf) |
| 9 | [Lottery Scheduling](01-virtualization/09-cpu-sched-lottery.pdf) |
| 10 | [Multi-CPU Scheduling](01-virtualization/10-cpu-sched-multi.pdf) |
| 11 | [Summary](01-virtualization/11-cpu-dialogue.pdf) |
| 12 | [Dialogue](01-virtualization/12-dialogue-vm.pdf) |
| 13 | [Address Spaces](01-virtualization/13-vm-intro.pdf) |
| 14 | [Memory API](01-virtualization/14-vm-api.pdf) |
| 15 | [Address Translation](01-virtualization/15-vm-mechanism.pdf) |
| 16 | [Segmentation](01-virtualization/16-vm-segmentation.pdf) |
| 17 | [Free Space Management](01-virtualization/17-vm-freespace.pdf) |
| 18 | [Introduction to Paging](01-virtualization/18-vm-paging.pdf) |
| 19 | [Translation Lookaside Buffers](01-virtualization/19-vm-tlbs.pdf) |
| 20 | [Advanced Page Tables](01-virtualization/20-vm-smalltables.pdf) |
| 21 | [Swapping: Mechanisms](01-virtualization/21-vm-beyondphys.pdf) |
| 22 | [Swapping: Policies](01-virtualization/22-vm-beyondphys-policy.pdf) |
| 23 | [Complete VM Systems](01-virtualization/23-vm-complete.pdf) |
| 24 | [Summary](01-virtualization/24-vm-dialogue.pdf) |

## Concurrency

| Chapter | Reading |
| --- | --- |
| 25 | [Dialogue](02-concurrency/25-dialogue-concurrency.pdf) |
| 26 | [Concurrency and Threads](02-concurrency/26-threads-intro.pdf) |
| 27 | [Thread API](02-concurrency/27-threads-api.pdf) |
| 28 | [Locks](02-concurrency/28-threads-locks.pdf) |
| 29 | [Locked Data Structures](02-concurrency/29-threads-locks-usage.pdf) |
| 30 | [Condition Variables](02-concurrency/30-threads-cv.pdf) |
| 31 | [Semaphores](02-concurrency/31-threads-sema.pdf) |
| 32 | [Concurrency Bugs](02-concurrency/32-threads-bugs.pdf) |
| 33 | [Event-based Concurrency](02-concurrency/33-threads-events.pdf) |
| 34 | [Summary](02-concurrency/34-threads-dialogue.pdf) |

## Persistence

| Chapter | Reading |
| --- | --- |
| 35 | [Dialogue](03-persistence/35-dialogue-persistence.pdf) |
| 36 | [I/O Devices](03-persistence/36-file-devices.pdf) |
| 37 | [Hard Disk Drives](03-persistence/37-file-disks.pdf) |
| 38 | [Redundant Disk Arrays (RAID)](03-persistence/38-file-raid.pdf) |
| 39 | [Files and Directories](03-persistence/39-file-intro.pdf) |
| 40 | [File System Implementation](03-persistence/40-file-implementation.pdf) |
| 41 | [Fast File System (FFS)](03-persistence/41-file-ffs.pdf) |
| 42 | [FSCK and Journaling](03-persistence/42-file-journaling.pdf) |
| 43 | [Log-structured File System (LFS)](03-persistence/43-file-lfs.pdf) |
| 44 | [Flash-based SSDs](03-persistence/44-file-ssd.pdf) |
| 45 | [Data Integrity and Protection](03-persistence/45-file-integrity.pdf) |
| 46 | [Summary](03-persistence/46-file-dialogue.pdf) |
| 47 | [Dialogue](03-persistence/47-dialogue-distribution.pdf) |
| 48 | [Distributed Systems](03-persistence/48-dist-intro.pdf) |
| 49 | [Network File System (NFS)](03-persistence/49-dist-nfs.pdf) |
| 50 | [Andrew File System (AFS)](03-persistence/50-dist-afs.pdf) |
| 51 | [Summary](03-persistence/51-dist-dialogue.pdf) |
