# QNX Neutrino RTOS Experiments

A structured record of practical work with the QNX Neutrino real-time operating system. The repository is organised by experiment number and topic.

## Experiment index

| Experiment | Topic | Core concepts |
|---|---|---|
| [101](Experiment-101/README.md) | Hello World on QNX VM and Raspberry Pi | QNX environment, cross-compilation, deployment |
| [201](Experiment-201/README.md) | Process creation with `fork()` | Processes, parent-child relationships, PIDs |
| [202](Experiment-202/README.md) | Thread coordination with condition variables | POSIX threads, mutexes, condition variables, state machines |
| [301](Experiment-301/README.md) | Client-server message passing | Channels, connections, `MsgSend`, `MsgReceive`, `MsgReply` |
| [401](Experiment-401/README.md) | Interrupt handling | Interrupt attachment and interrupt waiting |
| [402](Experiment-402/README.md) | Repeating timer with pulse messages | POSIX timers, QNX pulses, periodic event handling |

## Repository layout

- `Experiment-1xx/`: initial QNX environment and application work
- `Experiment-2xx/`: process and thread execution
- `Experiment-3xx/`: inter-process communication
- `Experiment-4xx/`: interrupt and timer mechanisms
- `Index/`: course laboratory index and supporting material

## Build and execution notes

- These experiments target QNX Neutrino. Linux examples are not automatically interchangeable with QNX.
- Build using the QNX toolchain and the target configuration documented in each experiment.
- Hardware-specific behaviour depends on the BSP, target image, permissions, and device support.
- Treat expected output as illustrative; verify behaviour on the actual target.

## Scope

This repository documents learning experiments. It is not a certified real-time, safety-critical, or flight-qualified software baseline.
