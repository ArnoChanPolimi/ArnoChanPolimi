# Politecnico di Milano · 2024-2026

`M.Sc. Telecommunication Engineering · Milan, Italy`

I came to Milan in 2024 for Telecommunication Engineering. At the beginning, it was not some cinematic arrival. It was paperwork, rent, metro lines, new classrooms, Italian signs, and the small daily work of figuring things out without making a mess.

Then the city started to become familiar. Not all at once. More like a map drawn by repetition: the same tram stop, the same campus corridors, the same walk after a long lab, the same view of old stone and modern engineering living side by side.

<p align="center">
  <img width="210" src="../assets/photos/Polimi/Polimi_1stBuilding.jpg" alt="Politecnico di Milano">
  <br><sub>Politecnico di Milano</sub>
</p>

PoliMi gave my interests a sharper shape. Wireless systems, signal processing, information theory, optimization, networks, machine learning infrastructure: different courses, but the same underlying question kept coming back.

**How does information move when the world is imperfect?**

That question is the thread I like most. It appears in noisy radar phase, in a wireless channel, in a feedback loop, in a congested network, and in distributed AI training when GPUs wait for data that has not arrived yet.

## Current Research

My current work is about **cross-geo communication for large-scale AI training**. The practical problem is simple and painful: when GPUs are separated by distance, synchronization and data exchange can become the bottleneck. Expensive hardware can spend too much time waiting.

I work with collective-communication libraries such as **NCCL**, **MSCCL**, and **ScaleCCL**, plus RDMA/RoCE-style networking and measurement scripts, to understand where time is lost and what can actually be improved.

What I like about this topic is that it does not let me hide behind nice words. A system either runs, stalls, saturates a link, exposes a bad assumption, or gives you a measurement worth trusting. That honesty is useful.

<p align="center">
  <img width="210" src="../assets/photos/Polimi/GPU_set.jpg" alt="The distributed-training test setup">
  <br><sub>The distributed-training test setup</sub>
</p>

## What I Take From PoliMi

- Measure first; intuition is better after it has met data.
- Good engineering is not only making things work, but understanding why they stop working.
- Communication systems are full of invisible movement. I like making that movement visible.

PoliMi has been the place where my interests in communication, signal processing, and AI infrastructure stopped feeling like separate tracks and started becoming one direction.

---

[← Back to profile](https://github.com/ArnoChanPolimi)
