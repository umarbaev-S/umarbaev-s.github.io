---
categories: ["0x13hrafnulf-challenges"]
title: "0x13hrafnulf's Challenges"
date: 2023-09-01
description: "Simple DLL injector with GUI"
author: "Sultan Umarbaev"
type: "post"
---

Who is [0x13hrafnulf](https://umarbaevb.github.io/)? 

# Simple DLL injector with GUI (dll-inj)
*in development*

Simple DLL injector with GUI written in C++ for educational purposes only
## Demo
![demo](./media/dll-inj/demo.gif)
## Code organization
- **GUI** - GUI management using [**Dear ImGui**](https://github.com/ocornut/imgui)
- **Injection** - DLL injection implemention using Windows API
- **OpenDialogBox** - file selection dialog box using Windows API
- **Proc** - process and process modules querying handler
- **Application** - application and app window management
## Description
[source code](https://github.com/umarbaev-S/dll-inj)
Coming soon...
#### Intro
Coming soon...
#### DLL Injection
Coming soon...
#### Dynamic data updates
Coming soon...

## Future plans
- Implement thread pool for thread reuse (currently a simple thread creation and deletion mechanism is utilized)
## References
- Windows process and its modules(dll) listing - https://learn.microsoft.com/en-us/windows/win32/toolhelp/taking-a-snapshot-and-viewing-processes
- Native Windows File Selection prompt - https://learn.microsoft.com/en-us/windows/win32/learnwin32/example--the-open-dialog-box
- Process injection - 
	- https://www.ired.team/offensive-security/code-injection-process-injection/dll-injection
	- https://ctfcracker.gitbook.io/process-injection/process-injection-part-2
	- https://tbhaxor.com/createremotethread-process-injection/
- ImGUI - https://github.com/ocornut/imgui