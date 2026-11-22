# Tiny Stack VM

A faithful interpreter of make.fun's tiny stack ISA: 32-bit wrapping integers, a
256-value stack, branches, calls, 256 words of memory, input and output, and all
ten traps with their own exit codes, in the reference VM's check order.

Run under Node 22: `node main.ts` reads every instance in `/input/<id>/`
(`program.bin` + `input.bin`) and writes `/output/<id>/stdout.bin` and
`/output/<id>/exit.txt`.

Competition page: https://make.fun/bounty/tiny-stack-vm-01-run-20261122
