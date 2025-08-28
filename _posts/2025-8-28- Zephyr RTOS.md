---
layout: post
title: Zephyr RTOS 
---
### Using Zephyr RTOS

#### References and requirements

It is mandatory that you have knowledge of C programming and microcontrollers.

A good reference for the tools used are presented  in the Shawn Hymel Series on the topic [this](https://www.digikey.com/en/maker/profiles/72825bdd887a427eaf8d960b6505adac).

To follow this tutorial properly, it’s recommended to have a GitHub account.

#### Motivations

Zephyr RTOS is a modern RTOS(Real Time Operating Systems). It is primarily licensed under the Apache License 2.0, a permissive open-source license that allows users to freely use, modify, distribute, and sell their own products, provided they preserve copyright and license notices. It has several drivers and boards integrated. It is more than a simple RTOS, it includes a complete build system.

**When to use Zephyr?** We can classify embedded systems as very small, small, medium, or large:

**Very Small Systems:** only one task, using microcontroller's resources and minimal requirements regarding storage and communications. In this case, a baremetal firmware can be used for accomplishing the task. No need of RTOS, perhaps a minimal scheduler is enough.

**Small Project:** multiple tasks, Wi-Fi/USB/Bluetooth communications, SD card storage, color displays. Developing everything from scratch would be a waste of time and resources. If the system is for a particular use and will not be modified in a long time, a small RTOS system as freeRTOS could achieve the goal in an acceptable fashion.

**Medium Project:** multiple tasks, OTA(over the air update), multiple storages (SD, disks, filesystems) and a Linux style system. This is where a more complex RTOS is needed, for example Zephyr RTOS.

**Large Project:** In case you need complex databases, multiple displays, multiple applications running in your embedded device, then the solution is a embedded Linux system. This system will have a subset of a complete Linux system allowing the device to perform in a similar way to a computer.

There is a very good explanation of the benefits of using Zephyr [here](https://sirinsoftware.com/blog/rtos-wars-freertos-vs-zephyr-a-decision-you-cant-afford-to-get-wrong).

#### Installing Zephyr tools

The build system relies on a special tool "west" and Cmake. For installing the system you must follow the  [official documentation](https://docs.zephyrproject.org/latest/develop/getting_started/index.html).

#### Upcoming posts

In the next post a new board based on esp32-wroom module will be configured.


<a href="gustavobastian.github.io/">gustavobastian.github.io</a> © 2025 by <a href="github.com/gustavobastian">Gustavo Bastian</a> is licensed under <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">