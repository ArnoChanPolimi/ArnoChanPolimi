### Hi, I'm Hong.

I'm a master's student in Telecommunication Engineering at **Politecnico di Milano**, working on distributed AI training in the [BONSAI Lab](https://www.bonsai.deib.polimi.it/) with [Qiaolun Zhang](https://qiaolunzhang.github.io/) and [Massimo Tornatore](https://tornatore.faculty.polimi.it/).

My thesis focuses on distributed AI training across datacenters, where the bandwidth available to GPU communication can change as network traffic varies. I study how collective communication schedules and WAN routing can adapt together to these changes.

I am building an experimental testbed using PyTorch FSDP, NCCL/MSCCL, and RDMA over RoCEv2. The work connects network measurements with decisions about All-Gather schedules and network paths. I use the testbed to compare communication time and training performance under changing bandwidth conditions, and to understand when adapting communication and routing together is useful.

<table>
<tr>
<td width="50%" align="center" valign="top"><a href="assets/thesis-payload-comparison.png" target="_blank" rel="noopener noreferrer"><img src="assets/thesis-payload-comparison.png" width="100%" alt="All-Gather latency across five workload sizes"></a><br><sub><strong>Across workload sizes</strong><br>Four control modes · All-Gather latency (ms)</sub></td>
<td width="50%" align="center" valign="top"><a href="assets/thesis-online-trace.png" target="_blank" rel="noopener noreferrer"><img src="assets/thesis-online-trace.png" width="100%" alt="Baseline and Fast+Slow All-Gather latency over 120 training steps"></a><br><sub><strong>During online operation</strong><br>Baseline vs. Fast+Slow · 120 training steps (s)</sub></td>
</tr>
</table>
<p><sub>Two separate experiments: workload scaling and an illustrative online run. Lower All-Gather latency is better. Click either figure to enlarge.</sub></p>

[Website](https://arnochanpolimi.github.io) · [LinkedIn](https://www.linkedin.com/in/hongchen-arno/) · [ORCID](https://orcid.org/0009-0005-2135-3301) · [Email](mailto:arnochan2024@gmail.com)

### Selected work

- **[NCCL / RDMA performance](https://github.com/ArnoChanPolimi/NCCL-RDMA-Performance-Tuning)** — Profiling and tuning collective communication for distributed training.
- **[Recommender systems](https://github.com/ArnoChanPolimi/RecSys_PoliMi_Challenge_2025)** — Combining sparse models on 3.8 million interactions.
- **[O-RAN control](https://github.com/ArnoChanPolimi/mrn-oran-m2-project2)** — Using radio measurements to guide modulation and coding decisions.
- **[Radar vital-sign sensing](https://github.com/ArnoChanPolimi/mmWave-Radar-Vital-Sign-Detection)** — Estimating breathing and heart rate from 77 GHz radar signals.

### Education

Three places I have studied, with stories and photographs from each.

<p><a href="https://github.com/ArnoChanPolimi/ArnoChanPolimi/blob/main/stories/polimi.md"><img src="assets/edu/polimi-badge.svg" width="38" height="38" align="absmiddle" alt="">&nbsp; <strong>Politecnico di Milano</strong></a>&nbsp; <img src="assets/flags/italy.svg" height="13" alt=""> — M.Sc. in Telecommunication Engineering<br><sub>Sep. 2024 – Dec. 2026 (expected)</sub></p>

<p><a href="https://github.com/ArnoChanPolimi/ArnoChanPolimi/blob/main/stories/ensea.md"><img src="assets/edu/ensea.svg" width="38" height="38" align="absmiddle" alt="">&nbsp; <strong>ENSEA, France</strong></a>&nbsp; <img src="assets/flags/france.svg" height="13" alt=""> — Erasmus exchange · Networks, wireless communications, and security<br><sub>Sep. 2025 – Jan. 2026</sub></p>

<p><a href="https://github.com/ArnoChanPolimi/ArnoChanPolimi/blob/main/stories/bit.md"><img src="assets/edu/bit.svg" width="38" height="38" align="absmiddle" alt="">&nbsp; <strong>Beijing Institute of Technology</strong></a>&nbsp; <img src="assets/flags/china.svg" height="13" alt=""> — B.Sc. in Electronic Information Engineering<br><sub>Sep. 2019 – Jun. 2023</sub></p>

### GitHub at a glance

<picture>
  <source media="(max-width: 760px) and (prefers-color-scheme: dark)" srcset="assets/stats-dark-mobile.svg">
  <source media="(max-width: 760px)" srcset="assets/stats-light-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <img src="assets/stats-light.svg" width="760" alt="GitHub snapshot: 21 public repositories, 5 followers, 1 repository star; language counts by repository.">
</picture>
