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
| [`switchctl`](https://github.com/cnberry/switchctl) | Local switch backends | named endpoints, roles, reachability, readiness | on/off and enable/disable |

The `*ctl` projects share the same shape: private configuration, compact human
output, safe JSON for automation, explicit confirmation for mutations, post-
write readback, hardware-free tests, a language-neutral `script/install`
contract, and honest reporting when an integration is uncertain.

## Engineering interests

- systems and infrastructure
- local-first and terminal-first software
- practical home automation
- agent-driven workflows
- C, C++, Python, and Rust

<!-- cnberry/cnberry is the repository rendered on this GitHub profile. -->
