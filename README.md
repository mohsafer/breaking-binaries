# Breaking Binaries

<p align="center">
  <b>Breaking Binaries</b><br>
  <sub>A CTF-Style Handbook of Binary Exploitation, Reverse Engineering, and C Exploitation Techniques</sub>
</p>

<p align="center">
  <a href="https://youtu.be/9z0G2_3ok6w">
    <img src="https://img.youtube.com/vi/9z0G2_3ok6w/hqdefault.jpg" alt="Watch the binary exploitation class recording" width="480">
  </a>
</p>

<p align="center">
  <i>Short class walkthrough — exploit dev loop from recon to shell.</i>
</p>

---

**Breaking Binaries** is a 260+ page educational handbook for computer
science security classes. It teaches binary exploitation, reverse
engineering, and C exploitation techniques the way capture-the-flag
players actually learn them: every concept is motivated, shown in the
smallest possible vulnerable target, practised as a CTF challenge, and
then hardened against the defenses a real binary will have.

**Author:** Mohammad Mosafer · **Version:** v1.2.0 (build 4) · **Length:** 260+ pages

**DOI:** [10.5281/zenodo.23963446](https://doi.org/10.5281/zenodo.23963446)

> ⚠️ **Educational use only.** Every technique here is illegal to apply
> against systems you do not own or are not explicitly authorized to
> test. All practice must happen in sandboxed lab environments (see the
> Disclaimer page inside the book).

## What this handbook covers

How programs live in memory, how C programs go wrong, and how security
students learn to find and exploit those mistakes — from the first
buffer overflow to format strings, stack canaries, return-to-libc,
ASLR/PIE bypasses, ROP chains, heap attacks, remote exploitation,
reverse engineering with the modern tool arsenal (Ghidra, IDA, radare2,
pwndbg), kernel and Windows primers, real-world case studies, and the
defender's countermeasures. Every technique is taught through small,
self-contained CTF-style challenges with full exploit scripts.

## Structure

| Part | Contents |
|------|----------|
| I–II | Foundations (memory, x86-64 assembly, ELF) and the tool arsenal (gdb, Ghidra, IDA, radare2, pwntools, lab setup) |
| III | Attacking the stack: overflows, shellcode, format strings, canaries, ret2libc, ASLR/PIE, ROP, advanced ROP |
| IV–V | Integer bugs; the heap (allocator internals, UAF, double free, tcache poisoning) |
| VI | Remote exploitation; fuzzing, symbolic execution, hybrid pipelines |
| VII | Reverse engineering: static, dynamic, anti-analysis |
| VIII | Modern mitigations, secure coding in C, the wider security landscape |
| IX–XII | CTF playbook and walkthroughs, landmark CVE case studies, Windows & kernel primers, masterclasses, ARM64, other runtimes, mobile |
| Appendices | Cheat sheets, lab source bundle, exams with answer keys, crash triage, and more |

36 CTF-style challenges, 40+ full exploit scripts, ~30 TikZ memory
diagrams, instructor's guide, exams with answer keys.

## Getting the book

The compiled book is [`binary_bookv1.0.pdf`](binary_bookv1.0.pdf) —
cover included, 260+ pages, A4.
