# Surface Hotplug Driver

Hotplug and D3cold support for the discrete GPU on Microsoft Surface Book 2 and 3 devices.

The Surface Hotplug driver (and corresponding patches) enable automatic runtime power management for the discrete GPU (dGPU) found on Microsoft Surface Book 2 and 3 devices, including D3cold support.
With the patches provided in this repository, the dGPU can be turned off completely by the kernel when not in use, leading to significant power savings.
Some configuration may however be required to acheive this.

Please refer to the [wiki](https://github.com/linux-surface/surface-hotplug/wiki) for more details.
