# NASM Assembly

Some samples and tutorial for NASM assembly language.

## Jumping

| Instruction | Meaning                               |
|-------------|---------------------------------------|
| `jne`       | **j**ump if **n**ot **e**qual.        |
| `je`        | **j**ump if **e**qual.                |
| `jg`        | **j**ump if **g**reater.              |
| `jle`       | **j**ump if **l**ess or **e**qual.    |
| `jl`        | **j**ump if **l**ess.                 |
| `jge`       | **j**ump if **g**reater or **e**qual. |

```nasm
cmp eax, 1
je one
jne two
```
