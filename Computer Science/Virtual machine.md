---
date: 2023-09-12
draft: false
tags:
  - definition
  - computer-science
---
# Definition

The emulation of a computer system.

# Notes

- Based on computer architectures.
- Provide the functionality of a physical computer.

There are two types:
- [[System virtual machine]]
- [[Process virtual machine]]

Benefits:
- Multiple guests operating system can be used on the same computer.
- Different instruction set architectures can be emulated on a single computer.
- Crush without affecting the [[Host]].
- Security.
- Cost saving due to not needing to purchase extra hardware.
- Run legacy software that are currently incompatible.

Drawbacks:
- Less efficient.
- Performance of the [[Guest]] cannot be adequately measured.
- Performance of the [[Host]] is reduced.
- Cannot emulate same hardware.