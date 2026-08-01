<h1 align="center">Hi! I'm Kiyanoush!</h1>

<p align="center">
  Kiyanoush (DEHSHAT) Bayar &middot; systems software developer
</p>

And this is my markdown page. Nothing special written, just a bunch of personal repos for people to see.

### What I do

I write low-level systems code — kernels, memory management, device models, filesystems, schedulers. Mostly C and assembly, mostly from scratch, mostly because it's fun to find out how far you can get without leaning on anyone else's OS.

### Things I'm building

**[Robu Microkernel](https://github.com/bayar17/robu_kernel)** — a fast microkernel written from scratch, no existing OS used as a reference. The whole point is to engineer around the real costs of a microkernel: IPC, virtual memory, scheduling, and interrupt handling. Register-based short messages, synchronous rendezvous with timeslice donation, page faults delegated to a user-space pager, lazy scheduling with direct switch. Targets armv7/armv8, x86_64, i386/i486 and riscv32/riscv64 — and it should still be quick on hardware nobody wants anymore. POSIX-like API on top so it's actually pleasant to develop against. MIT.

### Elsewhere

- GitHub: ![@bayar17](https://github.com/bayar17)
- Reddit: ![@seenhokage](https://www.reddit.com/user/seenhokage)

<p align="center">
  <sub>Two kernels going at once is a reasonable number of kernels.</sub>
</p>
