# OpenIPC FAQ

This FAQ provides a starting point for your documentation efforts. Questions are visible by default, and answers are hidden until expanded.

## General Questions about OpenIPC

<details>
  <summary>What is OpenIPC?</summary>
  
  OpenIPC is described as a non‑profit one‑stop‑shop for communication and experimentation for everyone who uses IP cameras for surveillance, medicine, robotics, FPV and other things. It is also referred to as a DIY project and a Linux operating system based on Buildroot/OpenWrt projects. OpenIPC is primarily intended to replace proprietary camera firmware, as well as to install firmware on newly created devices. It can be seen as a chassis and a designer from which various solutions can be built.
</details>

<details>
  <summary>Is OpenIPC a commercial project?</summary>
  
  No, OpenIPC is not a commercial project, not a company, but an officially registered community. It is a non‑profit community at the moment. The goal was initially to create a community, not an organisation or a company.
</details>

<details>
  <summary>How can I contribute to OpenIPC?</summary>
  
  You can help by writing better documentation, proofreading and correcting websites, testing, describing your working OpenIPC system in the wiki, making compact additions and corrections to documentation, and sharing your findings. Contributing to documentation is highly encouraged. You can also contribute code. There are contribution guidelines available.
</details>

<details>
  <summary>Where can I find OpenIPC documentation?</summary>
  
  The main documentation resources are the OpenIPC Wiki on GitHub at [https://github.com/openipc/wiki](https://github.com/openipc/wiki) and the new documentation site [docs.openipc.org](https://docs.openipc.org). The Wiki contains various documentation and instructions, but some of it is outdated and needs to be cleaned/updated/merged. The new documentation site has a better search function, and new information should ideally go there. There are also notes available on GitHub.
</details>

<details>
  <summary>What are the main development areas of OpenIPC?</summary>
  
  OpenIPC has several areas including Video Surveillance, FPV, and Home Automation. These areas are intertwined, sharing things like board firmware. The project is also focused on developing solutions for working with video on specialised processors.
</details>

<details>
  <summary>What are the communication channels for OpenIPC?</summary>
  
  The main communication channel is Telegram. There are several Telegram groups including an international channel for general development discussion, a development channel, and a channel for FPV users. Links to these and other channels can be found on the OpenIPC website at [https://openipc.org](https://openipc.org) and in the Wiki.
</details>

## OpenIPC FPV Specific Questions

<details>
  <summary>What is OpenIPC FPV?</summary>
  
  OpenIPC FPV refers to the use of OpenIPC firmware and hardware for First Person View applications, primarily in drones. It involves developing hardware and software specifically for FPV.
</details>

<details>
  <summary>What are the goals of OpenIPC FPV?</summary>
  
  The goal is to provide a flexible and open system for FPV, allowing users to experiment and participate in something different and innovative with cheap widely available components. There's a desire for OpenIPC to become the defacto standard for FPV.
</details>

<details>
  <summary>Which firmware can I use for FPV?</summary>
  
  Current options include firmware based on WFB‑NG (wifibroadcast next generation) and Ruby FPV. OpenIPC provides a platform that supports different solutions like WFB‑NG and Ruby.
</details>

<details>
  <summary>Where can I find documentation for OpenIPC FPV?</summary>
  
  FPV‑specific documentation can be found in the OpenIPC Wiki under the FPV section at [https://github.com/OpenIPC/wiki?tab=readme-ov-file#fpv](https://github.com/OpenIPC/wiki?tab=readme-ov-file#fpv). There are also specific how‑to guides, for example, on building OpenIPC with the 8812eu driver.
</details>

<details>
  <summary>What about latency in OpenIPC FPV?</summary>
  
  Latency can be around 80–100ms with 60fps. For lower latency, users should use 120fps encoding/decoding and a 120Hz monitor. OpenIPC doesn't want to state official latency figures due to the responsibility of measurement.
</details>

<details>
  <summary>Is there a WebUI for OpenIPC FPV firmware?</summary>
  
  Currently, OpenIPC FPV firmware does not have a WebUI. The main interface for setup and recovery is SSH. There might be a small stub for basic web interface functionality in the future.
</details>

<details>
  <summary>How can I get help with setting up OpenIPC FPV?</summary>
  
  You can ask questions in the OpenIPC FPV users Telegram group. It's recommended to read the documentation first as many questions have been discussed before. There are also community members willing to help.
</details>

<details>
  <summary>What hardware is supported for OpenIPC FPV?</summary>
  
  OpenIPC supports a variety of hardware, and new devices are constantly being developed. Examples mentioned include SSC30KQ and SSC338Q. The OpenIPC AIO "Mario" is a newer board. Compatibility with third‑party cables is being explored.
</details>

<details>
  <summary>What is MSP OSD?</summary>
  
  MSP OSD (On‑Screen Display) is a feature that allows displaying flight controller information in the video feed. OpenIPC has a project called msposd on GitHub. There is discussion about integrating OSD setup from INAV/Betaflight.
</details>

<details>
  <summary>What is wifibroadcast/wfb-ng?</summary>
  
  WFB‑NG is the next generation of long‑range packet radio link based on raw WiFi radio. It's a communication method used in OpenIPC FPV. Setup can be done using `wfb_cli gs`.
</details>

<details>
  <summary>What is Ruby FPV?</summary>
  
  Ruby FPV is another digital FPV system that OpenIPC cameras can be used with. There is a separate discussion thread for Ruby.
</details>

## Documentation Related Questions

<details>
  <summary>Why is documentation important for OpenIPC?</summary>
  
  Documentation is crucial for making OpenIPC easier to use for beginners, attracting more pilots, and for the overall growth and understanding of the project. The lack of standardization and documentation is seen as a weakness.
</details>

<details>
  <summary>Where is the OpenIPC Wiki?</summary>
  
  The OpenIPC Wiki is located on GitHub at [https://github.com/openipc/wiki](https://github.com/openipc/wiki).
</details>

<details>
  <summary>Where is the new OpenIPC documentation site (Docs)?</summary>
  
  The new documentation site is at [https://docs.openipc.org/](https://docs.openipc.org/).
</details>

<details>
  <summary>How can I contribute to OpenIPC documentation?</summary>
  
  You can contribute by creating a GitHub account, forking the Wiki repository, adding content in Markdown format, and submitting a pull request (PR). For the new documentation site, the process is similar, and contributors are welcome.
</details>

<details>
  <summary>What kind of information should be in the documentation?</summary>
  
  The documentation should include step‑by‑step instructions for beginners, clear explanations of setup procedures, information on hardware compatibility, configuration details, and answers to frequently asked questions. Practical examples and real‑world setups are valuable.
</details>

<details>
  <summary>Is the existing documentation up-to-date?</summary>
  
  No, much of the wiki is already outdated and needs to be cleaned/updated/merged. The project has declared 2024 the year of technical documentation. Efforts are underway to improve and migrate content to the new documentation site.
</details>

<details>
  <summary>Are there any guidelines for contributing to documentation?</summary>
  
  There aren't strict coding conventions, but a general rule is "don't be a dick". Instructions should be simple, repeatable, and ideally in a single file for each type of equipment. Formatting rules and requirements for pictures might be defined as part of the documentation effort.
</details>

## Technical/Setup Questions (Common Themes)

<details>
  <summary>Build process:</summary>
  
  The build process itself is considered to be "for geeks", and there is an intention to document it. A building manual exists in the wiki.
</details>

<details>
  <summary>Flashing firmware (burn tool):</summary>
  
  The burn tool is used for flashing firmware. There is a burn example in the Wiki and a YouTube playlist with tutorials. Instructions for beginners are being worked on.
</details>

<details>
  <summary>SSH access:</summary>
  
  SSH is the main interface for setup and recovery. Some people might not know how to spell it.
</details>

<details>
  <summary>WiFi configuration:</summary>
  
  WiFi card compatibility is a common question. Some drivers like `rtl_wfb` are used.
</details>

<details>
  <summary>Telemetry:</summary>
  
  Getting telemetry working is a topic of discussion.
</details>

<details>
  <summary>OSD setup:</summary>
  
  Configuring and displaying the OSD is relevant, especially with integration to flight controllers.
</details>

<details>
  <summary>Audio support:</summary>
  
  Some hardware like the SSC30KQ supports audio.
</details>

<details>
  <summary>Dual camera support:</summary>
  
  There is interest in dual camera setups.
</details>

<details>
  <summary>Integration with other systems (INAV/Betaflight, Home Assistant):</summary>
  
  Integrating OpenIPC with flight controller firmware like INAV and Betaflight for OSD and with home automation systems like Home Assistant via MQTT is explored.
</details>

<details>
  <summary>Latency:</summary>
  
  Latency is a key consideration for FPV users.
</details>
