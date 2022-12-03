Our project is spread over many repositories in order to focus on a limited
scope per repository.

This repository
(**[nerves-project/nerves](https://github.com/nerves-project/nerves)**) is an
entrance to Nerves and provides the core tooling and documentation.

The Nerves core team maintains the projects in the `nerves-project` organization
with the help of many in the Elixir community. Projects under other GitHub
organizations are maintained by their respective organization, but listed here
since they're so commonly used in conjunction with the core libraries and tools.

### Framework / Core

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[Erlinit](https://github.com/nerves-project/erlinit)** | Replacement for /sbin/init that launches an Erlang/OTP Release | ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/nerves-project/erlinit?sort=semver) |
| **[Nerves.Bootstrap](https://github.com/nerves-project/nerves_bootstrap)** | The Nerves new project generator and low level hooks into Mix | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_bootstrap.svg)](https://hex.pm/packages/nerves_bootstrap) |
| **[Nerves.Runtime](https://github.com/nerves-project/nerves_runtime)** | Small, general runtime utilities for Nerves devices | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_runtime.svg)](https://hex.pm/packages/nerves_runtime) |
| **[NervesPack](https://github.com/nerves-project/nerves_pack)** | Initialization setup for Nerves devices | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_pack.svg)](https://hex.pm/packages/nerves_pack) |
| **[NervesSystemBR](https://github.com/nerves-project/nerves_system_br)** | Buildroot based build platform for Nerves Systems | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_br.svg)](https://hex.pm/packages/nerves_system_br) |
| **[RingLogger](https://github.com/nerves-project/ring_logger)** | A ring buffer backend for Elixir Logger with IO streaming | [![Hex.pm](https://img.shields.io/hexpm/v/ring_logger.svg)](https://hex.pm/packages/ring_logger) |

### Example projects

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[Circuits Quickstart](https://github.com/elixir-circuits/circuits_quickstart)** | Try out Elixir Circuits with prebuilt Nerves firmware | ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/elixir-circuits/circuits_quickstart?sort=semver) |
| **[NervesExamples](https://github.com/nerves-project/nerves_examples)** | Small example programs using Nerves | |
| **[Nerves Livebook](https://github.com/livebook-dev/nerves_livebook)** | Develop on embedded devices with Livebook and Nerves | ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/livebook-dev/nerves_livebook?sort=semver) |

### Hardware

These are the officially supported hardware ports. Many others exist in the
community.

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[NervesSystemBBB](https://github.com/nerves-project/nerves_system_bbb)** | Base Nerves system configuration for the BeagleBone-based boards | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_bbb.svg)](https://hex.pm/packages/nerves_system_bbb) |
| **[NervesSystemOSD32MP1](https://github.com/nerves-project/nerves_system_osd32mp1)** | Base system for Octavo OSD32MP1 | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_osd32mp1.svg)](https://hex.pm/packages/nerves_system_osd32mp1) |
| **[NervesSystemRPi](https://github.com/nerves-project/nerves_system_rpi)** | Base Nerves system configuration for the Raspberry Pi A+ and B+ | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_rpi.svg)](https://hex.pm/packages/nerves_system_rpi) |
| **[NervesSystemRPi0](https://github.com/nerves-project/nerves_system_rpi0)** | Base Nerves system configuration for the Raspberry Pi Zero and Zero W | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_rpi0.svg)](https://hex.pm/packages/nerves_system_rpi0) |
| **[NervesSystemRPi2](https://github.com/nerves-project/nerves_system_rpi2)** | Base Nerves system configuration for the Raspberry Pi 2 | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_rpi2.svg)](https://hex.pm/packages/nerves_system_rpi2) |
| **[NervesSystemRPi3](https://github.com/nerves-project/nerves_system_rpi3)** | Base Nerves system configuration for the Raspberry Pi 3 | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_rpi3.svg)](https://hex.pm/packages/nerves_system_rpi3) |
| **[NervesSystemRPi3A](https://github.com/nerves-project/nerves_system_rpi3a)** | Nerves system for the Raspberry Pi 3 Model A+ w/ gadget mode and Raspberry Pi Zero 2 W | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_rpi3a.svg)](https://hex.pm/packages/nerves_system_rpi3a) |
| **[NervesSystemRPi4](https://github.com/nerves-project/nerves_system_rpi4)** | Base Nerves system configuration for the Raspberry Pi 4 | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_rpi4.svg)](https://hex.pm/packages/nerves_system_rpi4) |
| **[NervesSystemVultr](https://github.com/nerves-project/nerves_system_vultr)** | Experimental configuration for a Vultr cloud server | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_vultr.svg)](https://hex.pm/packages/nerves_system_vultr) |
| **[NervesSystemX86_64](https://github.com/nerves-project/nerves_system_x86_64)** | Generic Nerves system configuration x86_64 based hardware | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_x86_64.svg)](https://hex.pm/packages/nerves_system_x86_64) |
| **[NervesSystemGrisp2](https://github.com/nerves-project/nerves_system_grisp2)** |Base Nerves system configuration for the GRiSP 2 | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_grisp2.svg)](https://hex.pm/packages/nerves_system_grisp2) |

### Networking

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[VintageNet](https://github.com/nerves-networking/vintage_net)** | Network configuration and management for Nerves | [![Hex.pm](https://img.shields.io/hexpm/v/vintage_net.svg)](https://hex.pm/packages/vintage_net) |
| **[VintageNetWiFi](https://github.com/nerves-networking/vintage_net_wifi)** | WiFi networking for VintageNet | [![Hex.pm](https://img.shields.io/hexpm/v/vintage_net_wifi.svg)](https://hex.pm/packages/vintage_net_wifi) |
| **[VintageNetDirect](https://github.com/nerves-networking/vintage_net_direct)** | Direct network connection support for VintageNet | [![Hex.pm](https://img.shields.io/hexpm/v/vintage_net_direct.svg)](https://hex.pm/packages/vintage_net_direct) |
| **[VintageNetEthernet](https://github.com/nerves-networking/vintage_net_ethernet)** | Ethernet support for VintageNet | [![Hex.pm](https://img.shields.io/hexpm/v/vintage_net_ethernet.svg)](https://hex.pm/packages/vintage_net_ethernet) |
| **[VintageNetMobile](https://github.com/nerves-networking/vintage_net_mobile)** | Mobile connection support for VintageNet | [![Hex.pm](https://img.shields.io/hexpm/v/vintage_net_mobile.svg)](https://hex.pm/packages/vintage_net_mobile) |
| **[VintageNetQMI](https://github.com/nerves-networking/vintage_net_qmi)** | VintageNet technology support for QMI mobile connections | [![Hex.pm](https://img.shields.io/hexpm/v/vintage_net_qmi.svg)](https://hex.pm/packages/vintage_net_qmi) |
| **[VintageNetWireGuard](https://github.com/nerves-networking/vintage_net_wireguard)** | Wireguard VPN support | [![Hex.pm](https://img.shields.io/hexpm/v/vintage_net_wireguard.svg)](https://hex.pm/packages/vintage_net_wireguard) |

### Hardware access

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[Circuits.GPIO](https://github.com/elixir-circuits/circuits_gpio)** | Use GPIOs in Elixir | [![Hex.pm](https://img.shields.io/hexpm/v/circuits_gpio.svg)](https://hex.pm/packages/circuits_gpio) |
| **[Circuits.I2C](https://github.com/elixir-circuits/circuits_i2c)** | Use I2C in Elixir | [![Hex.pm](https://img.shields.io/hexpm/v/circuits_i2c.svg)](https://hex.pm/packages/circuits_i2c) |
| **[Circuits.SPI](https://github.com/elixir-circuits/circuits_spi)** | Communicate over SPI from Elixir | [![Hex.pm](https://img.shields.io/hexpm/v/circuits_spi.svg)](https://hex.pm/packages/circuits_spi) |
| **[Circuits.UART](https://github.com/elixir-circuits/circuits_uart)** | Discover and use UARTs and serial ports in Elixir | [![Hex.pm](https://img.shields.io/hexpm/v/circuits_uart.svg)](https://hex.pm/packages/circuits_uart) |

### SSH and Shell

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[NervesMOTD](https://github.com/nerves-project/nerves_motd)** | Message of the day for Nerves devices | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_motd.svg)](https://hex.pm/packages/nerves_motd) |
| **[NervesSSH](https://github.com/nerves-project/nerves_ssh)** | Manage an SSH daemon and subsystems on Nerves devices | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_ssh.svg)](https://hex.pm/packages/nerves_ssh) |
| **[SSHSubsystemFwup](https://github.com/nerves-project/ssh_subsystem_fwup)** | Erlang SSH Subsystem for Nerves firmware updates | [![Hex.pm](https://img.shields.io/hexpm/v/ssh_subsystem_fwup.svg)](https://hex.pm/packages/ssh_subsystem_fwup) |
| **[Toolshed](https://github.com/elixir-toolshed/toolshed)** | A toolshed of shell-like IEx helpers | [![Hex.pm](https://img.shields.io/hexpm/v/toolshed.svg)](https://hex.pm/packages/toolshed) |

### Toolchain

Nerves provides a C/C++ cross-toolchain to ensure consistency builds on all
supported host platforms. These are built using
[crosstool-ng](https://github.com/crosstool-ng/crosstool-ng) and are similar to
other GCC toolchains.

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
|  **[nerves_toolchain_ctng](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_ctng)** | Crosstool-NG integration for building Nerves toolchains | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_ctng.svg)](https://hex.pm/packages/nerves_toolchain_ctng) |
|  **[nerves_toolchain_aarch64_nerves_linux_gnu](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_aarch64_nerves_linux_gnu)** | 64-bit ARM toolchain | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_aarch64_nerves_linux_gnu.svg)](https://hex.pm/packages/nerves_toolchain_aarch64_nerves_linux_gnu) |
|  **[nerves_toolchain_armv5_nerves_linux_musleabi](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_armv5_nerves_linux_musleabi)** | 32-bit ARM toolchain for older ARM processors | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_armv5_nerves_linux_musleabi.svg)](https://hex.pm/packages/nerves_toolchain_armv5_nerves_linux_musleabi) |
|  **[nerves_toolchain_armv6_nerves_linux_gnueabihf](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_armv6_nerves_linux_gnueabihf)** | 32-bit ARM toolchain for Raspberry Pi A, B, and Zero | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_armv6_nerves_linux_gnueabihf.svg)](https://hex.pm/packages/nerves_toolchain_armv6_nerves_linux_gnueabihf) |
|  **[nerves_toolchain_armv7_nerves_linux_gnueabihf](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_armv7_nerves_linux_gnueabihf)** | 32-bit ARM toolchain for most 32-bit ARMs | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_armv7_nerves_linux_gnueabihf.svg)](https://hex.pm/packages/nerves_toolchain_armv7_nerves_linux_gnueabihf) |
|  **[nerves_toolchain_i586_nerves_linux_gnu](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_i586_nerves_linux_gnu)** | 32-bit Intel x86 toolchain | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_i586_nerves_linux_gnu.svg)](https://hex.pm/packages/nerves_toolchain_i586_nerves_linux_gnu) |
|  **[nerves_toolchain_mipsel_nerves_linux_musl](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_mipsel_nerves_linux_musl)** | 32-bit MIPS toolchain | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_mipsel_nerves_linux_musl.svg)](https://hex.pm/packages/nerves_toolchain_mipsel_nerves_linux_musl) |
|  **[nerves_toolchain_riscv64_nerves_linux_gnu](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_riscv64_nerves_linux_gnu)** | 64-bit RISC-V toolchain | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_riscv64_nerves_linux_gnu.svg)](https://hex.pm/packages/nerves_toolchain_riscv64_nerves_linux_gnu) |
|  **[nerves_toolchain_x86_64_nerves_linux_musl](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_x86_64_nerves_linux_musl)** | 64-bit x86 toolchain using the musl libc | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_x86_64_nerves_linux_musl.svg)](https://hex.pm/packages/nerves_toolchain_x86_64_nerves_linux_musl) |
|  **[nerves_toolchain_x86_64_nerves_linux_gnu](https://github.com/nerves-project/toolchains/tree/main/nerves_toolchain_x86_64_nerves_linux_gnu)** | 64-bit x86 toolchain using GNU libc | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_toolchain_x86_64_nerves_linux_gnu.svg)](https://hex.pm/packages/nerves_toolchain_x86_64_nerves_linux_gnu) |

### Miscellaneous

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[boardid](https://github.com/nerves-project/boardid)** | Print out a platform-specific board serial number | ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/nerves-project/boardid?sort=semver) |
| **[NervesFWLoaders](https://github.com/nerves-project/nerves_fw_loaders)** | A collection of firmware loaders for boards with internal storage | ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/nerves-project/nerves_fw_loaders?sort=semver) |
| **[NervesHeart](https://github.com/nerves-project/nerves_heart)** | Erlang heartbeat support for Nerves | ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/nerves-project/nerves_heart?sort=semver) |
| **[Shoehorn](https://github.com/nerves-project/shoehorn)** | Help handle OTP application failures and start order | [![Hex.pm](https://img.shields.io/hexpm/v/shoehorn.svg)](https://hex.pm/packages/shoehorn) |
| **[UBootEnv](https://github.com/nerves-project/uboot_env)** | Read and write to U-Boot environment blocks | [![Hex.pm](https://img.shields.io/hexpm/v/uboot_env.svg)](https://hex.pm/packages/uboot_env) |

### Upcoming

These projects are new or experimental and are in various stages of being ready
to promote to the above categories.

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[NervesLogging](https://github.com/nerves-project/nerves_logging)** | Route system log messages through the Elixir logger | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_logging.svg)](https://hex.pm/packages/nerves_logging) |
| **[NervesUEvent](https://github.com/nerves-project/nerves_uevent)** | Simple UEvent monitor for detecting hardware and automatically loading drivers | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_uevent.svg)](https://hex.pm/packages/nerves_uevent) |
| **[PropertyTable](https://github.com/jjcarstens/property_table)** | In-memory key-value store with subscriptions | [![Hex.pm](https://img.shields.io/hexpm/v/property_table.svg)](https://hex.pm/packages/property_table) |
| **[nerves_initramfs](https://github.com/nerves-project/nerves_initramfs)** | An initramfs for early boot handling of Nerves devices | ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/nerves-project/nerves_initramfs?sort=semver) |
| **[nerves_system_linter](https://github.com/nerves-project/nerves_system_linter)** | Mix task to check Nerves system configuration files | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_system_linter.svg)](https://hex.pm/packages/nerves_system_linter) |
| **[nerves_systems](https://github.com/nerves-project/nerves_systems)** | Build scripts for maintaining multiple repositories | _unreleased_ |

<details>
<summary><b>See outdated/inactive projects...</b></summary><br />

| Name | Description | Release |
| -------------------------: | :------------------------------------------------------------------------------------------ | :-------------------------------------------------------- |
| **[nerves_leds](https://github.com/nerves-project/nerves_leds)** | Functions to drive LEDs on embedded systems | [![Hex.pm](https://img.shields.io/hexpm/v/nerves_leds.svg)](https://hex.pm/packages/nerves_leds) |
| **[system_registry](https://github.com/nerves-project/system_registry)** | Serial nested term storage and dispatch registry | [![Hex.pm](https://img.shields.io/hexpm/v/system_registry.svg)](https://hex.pm/packages/system_registry) |
| **[system_registry_term_storage](https://github.com/nerves-attic/system_registry_term_storage)** | Simple term storage for SystemRegistry | [![Hex.pm](https://img.shields.io/hexpm/v/system_registry_term_storage.svg)](https://hex.pm/packages/system_registry_term_storage) |
| **[nerves_system_test](https://github.com/nerves-project/nerves_system_test)** | | |
| **[nerves_test_server](https://github.com/nerves-project/nerves_test_server)** | | |

There is also a gravesite for old Nerves libraries at
https://github.com/nerves-project-attic.

</details>
