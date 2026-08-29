# Embedded & Robotics — the day-job shelf

The day-job file. Firmware, RTOS, embedded Linux, silicon, robots. (Memfault Interrupt, Oxide, righto.com, Fabien Sanglard live in `blogs.md`; Ben Eater, Low Level, javidx9, EEVblog, w2aew, Marco Reps live in `youtube.md` — not duplicated here.)

## Prior art (mine these)

- [nhivp/Awesome-Embedded](https://github.com/nhivp/Awesome-Embedded) — the big one: architectures, tools, course notes.
- [embedded-boston/awesome-embedded-systems](https://github.com/embedded-boston/awesome-embedded-systems) — RTOSes, libraries, references; opinionated blurbs.
- [fkromer/awesome-embedded-linux](https://github.com/fkromer/awesome-embedded-linux) — bootloaders, build systems (Yocto/Buildroot), updates, security modules.
- [rust-embedded/awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) — no_std crates, BSPs, real firmware projects.
- [hexsecs/awesome-embedded-security](https://github.com/hexsecs/awesome-embedded-security) + [fkie-cad/awesome-embedded-and-iot-security](https://github.com/fkie-cad/awesome-embedded-and-iot-security) — firmware RE, side channels, secure boot.
- [ahundt/awesome-robotics](https://github.com/ahundt/awesome-robotics) + [Tinker-Twins/Robotics-Resources](https://github.com/Tinker-Twins/Robotics-Resources) — simulators, SLAM, motion planning, courses.
- [Phylliade/awesome-machine-learning-robotics](https://github.com/Phylliade/awesome-machine-learning-robotics) — ML-for-robotics papers/libraries.
- [natnew/awesome-physical-ai](https://github.com/natnew/awesome-physical-ai) — the VLA/Physical-AI stack map.

## Embedded / firmware blogs

- [Memfault Interrupt](https://interrupt.memfault.com/) — in `blogs.md`, but deserves repeating here: THE firmware-craft blog (Zephyr, RTOS internals, debugging, CI on hardware). `embedded`
- [Embedded Artistry (Phillip Johnston)](https://embeddedartistry.com/) — firmware architecture, safety, queue theory, field notes from real product work. `embedded` `design`
- [Jack Ganssle](https://www.ganssle.com/) — 40 years of embedded judgment + The Embedded Muse newsletter. Read the essays on watchdogs and resets. `embedded` `culture`
- [Quantum Leaps / Miro Samek](https://www.state-machine.com/) — event-driven firmware, state machines, free Cortex-M course (see YouTube below). `embedded` `rtos`
- [Embedded Gurus (Nigel Jones et al.)](https://embeddedgurus.com/) — multi-author embedded essays; the C trivia alone is worth it. `embedded` `c`
- [MCU on Eclipse (Erich Styger)](https://mcuoneclipse.com/) — relentless hands-on tutorials: STM32, NXP, Zephyr, FreeRTOS, toolchains. `embedded`
- [Beningo Embedded Group (Jacob Beningo)](https://www.beningo.com/) — embedded tips, RTOS migrations (FreeRTOS→Zephyr), industry trend write-ups. `embedded` `rtos`
- [Barr Group](https://www.barrgroup.com/) — Michael Barr; embedded coding standards, safety-critical practice. `embedded` `safety`
- [Shawn Hymel](https://www.shawnhymel.com/) — Zephyr, KiCad, wireless; the DigiKey Zephyr series author. `embedded` `tutorials`

## Embedded Linux / kernel

- [Bootlin](https://www.bootlin.com/blog/) — kernel, device trees, mainlining; their training materials are free and excellent. `embedded-linux` `kernel`
- [Pengutronix](https://www.pengutronix.de/en/blog.html) — Yocto, kernel, BSPs from the German embedded-Linux crew. `embedded-linux`
- [LWN.net](https://lwn.net/) — kernel development journalism; the weekly deep dives are unmatched. `kernel` `linux`
- [Zephyr Project](https://www.zephyrproject.org/) — project blog: releases, safety-cert work, ecosystem. `rtos`
- [Espressif Developer Blog](https://developer.espressif.com/blog/) — ESP-IDF internals, wireless stacks, RISC-V. `embedded`
- [Raspberry Pi News](https://www.raspberrypi.com/news/) — the RP2040/RP2350 datasheet-grade blog posts hide here. `embedded` `hardware`

## Hardware hacking / silicon / side channels

- [bunnie studios (Bunnie Huang)](https://www.bunniestudios.com/) — hardware reverse engineering, open hardware, Novena/Betrusted; the deepest hardware blog there is. `hardware` `sec`
- [Trammell Hudson](https://trmm.net/) — low-level hardware projects, firmware implants, THINK Center research. `hardware` `sec`
- [Colin O'Flynn](https://www.colinoflynn.com/) — ChipWhisperer author; side-channel analysis and fault injection on real chips. `sec` `hardware`

## Robotics — industry engineering blogs

- [Physical Intelligence (π)](https://www.pi.website/blog) — the π0/π0.5 VLA foundation-model posts; the frontier of robot learning. `robotics` `ml`
- [Hugging Face — LeRobot](https://huggingface.co/blog) — open-source robotics posts (LeKiwi, Reachy, SO-100 arms) inside the HF blog. `robotics` `ml`
- [Foxglove](https://foxglove.dev/blog) — robotics data/observability stack; their Actuate conference recaps double as a Physical-AI industry census. `robotics` `tools`
- [Wayve](https://wayve.ai/blog) — end-to-end learning for AVs; research-adjacent but engineering-honest. `robotics` `av`
- [Skydio](https://www.skydio.com/blog) — drone autonomy engineering; the autonomy-infrastructure posts are strong. `robotics` `av`
- [Waymo](https://waymo.com/blog) — the long game in AV; safety-framework posts. `av`
- [NVIDIA Developer Blog](https://developer.nvidia.com/blog/) — CUDA, Jetson, Isaac ROS/Isaac Sim — the robotics-adjacent compute stack. `robotics` `gpu`
- [Open Robotics](https://www.openrobotics.org/) — ROS 2 / Gazebo news from the source. `robotics` `ros`

## Robotics — pundits, research, media

- [Rodney Brooks](https://www.rodneybrooks.com/) — iRobot/Rethink founder; the annual Predictions Scorecard is required reading for anyone selling robot hype. `robotics` `culture`
- [IEEE Spectrum — Robotics](https://spectrum.ieee.org/robotics) — the best robotics journalism (video fridays, disasters, humanoids). `robotics`
- [Robohub](https://robohub.org/) — community-run news, research spotlights, podcasts. `robotics`
- [Underactuated Robotics — Russ Tedrake](https://underactuated.mit.edu/) — free MIT course-as-book on control; Drake lineage. `robotics` `control`
- [PythonRobotics (Atsushi Sakai)](https://atsushisakai.github.io/PythonRobotics/) — every classic robotics algorithm with runnable code. `robotics` `algorithms`

## Podcasts

- [Embedded.fm (Elecia White & Chris White)](https://embedded.fm/) — 400+ episodes of embedded engineering conversation; the field's water cooler. `embedded`
- [The Amp Hour (Chris Gammell & David Jones)](https://theamphour.com/) — electronics industry chatter and deep dives. `hardware`
- [The Robot Brains (Pieter Abbeel)](https://www.therobotbrains.ai/) — interviews with robotics/ML leaders. `robotics` `ml`

## YouTube — embedded & electronics

- [Phil's Lab](https://www.youtube.com/@PhilsLab) — PCB design + STM32/embedded firmware, end-to-end builds (KiCad, hardware bring-up). `embedded` `hardware`
- [DigiKey (Shawn Hymel's series)](https://www.youtube.com/@DigiKey) — the 12-part Zephyr RTOS course and Introduction to RTOS series. `rtos` `embedded`
- [Quantum Leaps (Miro Samek)](https://www.youtube.com/@quantumleaps) — "Modern Embedded Systems Programming": bare-metal ARM Cortex-M from reset vector up, in assembly then C. The best free embedded fundamentals course. `embedded` `arm`

## YouTube — robotics & mechanical

- [Articulated Robotics (Josh Newans)](https://www.youtube.com/@ArticulatedRobotics) — building a ROS 2 mobile robot from scratch: URDF, Nav2, simulation. The practical ROS 2 course. `ros` `robotics`
- [Skyentific](https://www.youtube.com/@Skyentific) — robot arms, actuators, cycloidal gearboxes; real mechanical robot engineering. `robotics` `mech`
- [Breaking Taps](https://www.youtube.com/@BreakingTaps) — precision engineering under the microscope (EDM, metallurgy, machining). `mech` `hardware`
- [James Bruton](https://www.youtube.com/@JamesBruton) — open-source humanoid/legged robot builds with real actuator trade-offs. `robotics`
- [Jeremy Fielding](https://www.youtube.com/@JeremyFielding) — mechanical engineering design in practice. `mech`
- [This Old Tony](https://www.youtube.com/@ThisOldTony) — machining with the best jokes in engineering YouTube. `mech`
- [Stuff Made Here](https://www.youtube.com/@StuffMadeHere) — absurd engineering builds; great for the "harder than it looks" lesson. `mech`
- [Berkeley CS285 (Sergey Levine)](https://www.youtube.com/@SergeyLevine?r) — Deep RL for robotics lectures; search "CS285 deep reinforcement learning playlist". `ml` `robotics` *(verify channel URL)*

## Unverified — to vet

*(inbox)*
- The Robot Brains — domain moved (301); find canonical URL. `robotics`
- CS285 / 16-745 (Zac Manchester, CMU Optimal Control) — pin canonical playlists.
- ETH Zurich RSL (Marco Hutter) — legged robotics research pages/news.
- Anduril — `/blog` 404'd; check if they have a newsroom with engineering substance.
- Ben Katz (MIT) — motor/actuator design posts (cheetah lineage); find stable home. `robotics` `mech`
- James Munns — jamesmunns.com/blog (verified 200) — decide embedded-Rust placement; candidate above.
- ZipCPU & Tom Verbeure (FPGA blogs, verified 200) — add if FPGA scope grows beyond hobby.
- interrupt memfault guest posts on Zephyr vs FreeRTOS — canonize 2–3 for the day-job reading list.
