![Open-CMSIS-Pack](/profile/Open-CMSIS-Pack.png)

## About Open-CMSIS-Pack

The Open-CMSIS-Pack project offers a flexible and easy to use end to end development flow for embedded software - from project creation to software execution on real or virtual hardware.

## List of Repositories

### Specifications

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [Open-CMSIS-Pack-Spec](https://github.com/Open-CMSIS-Pack/Open-CMSIS-Pack-Spec) | A specification describing a delivery mechanism for software components, device parameters, and evaluation board support. It also defines the build tools for projects based on software packs. | Access the [pre-built specification directly](https://open-cmsis-pack.github.io/Open-CMSIS-Pack-Spec/main/html/index.html). |
| [Open-CMSIS-CDI-Spec](https://github.com/Open-CMSIS-Pack/Open-CMSIS-CDI-Spec) | A set of APIs to enable firmware updates, running IoT applications, and RTOSes on a broad range of devices. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/Open-CMSIS-CDI-Spec) file. |

### Ready-to-use Tools

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [CMSIS-Toolbox](https://github.com/Open-CMSIS-Pack/cmsis-toolbox) | A set of command-line tools for software packs. | The [documentation](https://github.com/Open-CMSIS-Pack/cmsis-toolbox/blob/main/docs/README.md) explains the download, installation, and configuration process. |
| [gen-pack](https://github.com/Open-CMSIS-Pack/gen-pack) | A library for scripts creating Open-CMSIS-Packs. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/gen-pack) file. |
| [gen-pack-action](https://github.com/Open-CMSIS-Pack/gen-pack-action) | A GitHub workflow action generating documentation and Open-CMSIS-Packs. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/gen-pack-action) file. |
| [vidx2pidx](https://github.com/Open-CMSIS-Pack/vidx2pidx) | A package index generator. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/vidx2pidx) file. |

### Examples

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [csolution-examples](https://github.com/Open-CMSIS-Pack/csolution-examples) | A collection of exemplary csolution-based projects. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/csolution-examples) file. |

### Visual Studio Code

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [vscode-get-started](https://github.com/Open-CMSIS-Pack/vscode-get-started) | Setup of VS Code environment along wiht an example project. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/vscode-get-started) file. |

### Create Software Packs

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [SW-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/SW-Pack-HandsOn) | Explains the steps to create a simple software pack. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/SW-Pack-HandsOn) file. |
| [DFP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/DFP-Pack-HandsOn) | Explains the steps to create a device family pack. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/DFP-Pack-HandsOn) file. |
| [BSP-Pack-HandsOn](https://github.com/Open-CMSIS-Pack/BSP-Pack-HandsOn) | Explains the steps to create a board support pack. | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/BSP-Pack-HandsOn) file. |

### Pack Examples

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [Pack Examples](https://github.com/Open-CMSIS-Pack/pack-examples) | Examples of DFPs and BSP (mainly for STM32 devices/baords)  | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/pack-examples) file. |
| [lwIP](https://github.com/Open-CMSIS-Pack/lwIP) | lwIP Network Stack. | . |
| [CMSIS-Driver_STM32](https://github.com/Open-CMSIS-Pack/CMSIS-Driver_STM32) | Shim layers convert STM32HAL to CMSIS-Driver for MDK Middleware. | . |
| [NXP_iMXRT105x_MWP](https://github.com/Open-CMSIS-Pack/NXP_iMXRT105x_MWP) | NXP i.MXRT1051/1052 Device Series Middleware examples and CMSIS-Drivers Pack  | https://open-cmsis-pack.github.io/NXP_iMXRT105x_MWP |
| [NXP_IMXRT1050-EVKB_BSP](https://github.com/Open-CMSIS-Pack/NXP_IMXRT1050-EVKB_BSP) | NXP IMXRT1050-EVKB Board Support Pack | TBD |
| [ST_B-U585I-IOT02A_BSP](https://github.com/Open-CMSIS-Pack/ST_B-U585I-IOT02A_BSP) | STMicroelectronics ST_B-U585I-IOT02A Board Support Pack | https://github.com/Open-CMSIS-Pack/ST_B-U585I-IOT02A_BSP/tree/main/Documents#readme|
| [STM32H743I-Eval_BSP](https://github.com/Open-CMSIS-Pack/STM32H743I-EVAL_BSP) | STMicroelectronics STM32H743I-Eval Board Support Pack | TBD |
| [STM32H7xx_DFP](https://github.com/Open-CMSIS-Pack/STM32H7xx_DFP) | STMicroelectronics STM32H7 Series Device Family Pack | TBD |
| [STM32U5xx_DFP](https://github.com/Open-CMSIS-Pack/STM32U5xx_DFP) | STMicroelectronics STM32U5 Series Device Family Pack | TBD |
| [STM32H7S78-DK_BSP](https://github.com/Open-CMSIS-Pack/STM32H7S78-DK_BSP) | STMicroelectronics STM32H7S78-DK Board Support Pack | TBD |
| [STM32H7RSxx_DFP](https://github.com/Open-CMSIS-Pack/STM32H7RSxx_DFP) | STMicroelectronics STM32H7RS Series Device Family Pack | TBD |

### Tools Source Code

| Repository | Description | Documentation |
|------------|-------------|---------------|
| [devtools](https://github.com/Open-CMSIS-Pack/devtools) | Development repo of these command line tools: [packchk](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/packchk), [packgen](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/packgen), csloution ([projmgr](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/projmgr)), and cbuild ([buildmgr](https://github.com/Open-CMSIS-Pack/devtools/tree/main/tools/buildmgr)). | Contains the specification of the [csolution project format](https://github.com/Open-CMSIS-Pack/devtools/blob/main/tools/projmgr/docs/Manual/Overview.md) and related files. |
| [cpackget](https://github.com/Open-CMSIS-Pack/cpackget) | Source code repository of the cpackget tool (part of the CMSIS-Toolbox) | Refer to the [Readme.md](https://github.com/Open-CMSIS-Pack/cpackget) file. |



