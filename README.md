# Chris Berry

Engineer at OpenAI working on systems that help researchers move faster and
scale training.

I build small, terminal-first tools for real-world systems: commands that are
composable, explicit about state, careful around physical writes, and useful to
humans and agents alike.

## Control tools

| Project | System | Read surface | Guarded write surface |
| --- | --- | --- | --- |
| [`gatectl`](https://github.com/cnberry/gatectl) | LiftMaster/MyQ | accounts, devices, online and open/closed state | gate and garage-door open/close |
| [`poolctl`](https://github.com/cnberry/poolctl) | Pentair ScreenLogic | controller, bodies, circuits, pumps, cleaner, delays | cleaner on/off and delay cancel |
| [`hottubctl`](https://github.com/cnberry/hottubctl) | Sundance SmartTub | spas, connectivity, water/set temperature, freshness | target temperature |

The three projects share the same shape: private local configuration, compact
human output, JSON for automation, explicit confirmation for mutations, post-
write readback, hardware-free tests, and honest reporting when data is stale or
an unofficial integration is uncertain.

## Engineering interests

- systems and infrastructure
- local-first and terminal-first software
- practical home automation
- agent-driven workflows
- C, C++, Python, and Rust

<!-- cnberry/cnberry is the repository rendered on this GitHub profile. -->
