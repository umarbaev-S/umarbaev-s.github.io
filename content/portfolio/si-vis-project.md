+++
categories = ["personal"]
coders = []
date = 2023-08-01
description = "si-vis"
github = ["https://github.com/umarbaev-S/si-vis"]
image = "images/other/sys-info.png"
title = "System Info visualizer"
type = "post"
[[tech]]
logo = "https://raw.githubusercontent.com/umarbaev-S/umarbaev-s.github.io/master/static/images/skills/rust.svg"
name = "Rust"
url = "https://www.rust-lang.org/"

+++
# System Info visualizer (si-vis)
*in development*

Simple system info visualizer written in Rust for educational purposes only
## Dependency resolution
- [eframe](https://github.com/emilk/egui/tree/master/crates/eframe) - official framework library for writing apps using [egui](https://github.com/emilk/egui), GUI library for Rust
- [egui_dock](https://github.com/Adanos020/egui_dock) - library provides docking(tabs) support for `egui` 
- [egui_extras](https://docs.rs/egui_extras/latest/egui_extras/) - adds some features on top of `egui`, used for building table
- [sysinfo](https://github.com/GuillaumeGomez/sysinfo) - crate used to get a system's information
## Code organization
- `si_gui`, contains GUI app drawing and updating parts 
	- `si_data`, stores and updates system info data
## Screenshots
General system info tab
![sys-info-tab](../images/si-vis/sys-info-tab.jpg)

CPU and its usage info tab 
![cpu-info-tab](../images/si-vis/cpu-info-tab.jpg)

Processes info table tab
![processes-info-tab](../images/si-vis/processes-info-tab.jpg)
## Future plans
- Reorganize app layout
- Add sorting based on columns in processes info table
- Display memory allocations in real-time when specific process is selected (inspired by [mevi](https://github.com/fasterthanlime/mevi))