# Cowboy Firmware Catalog

## Notice

This repository is an unofficial archive of Cowboy firmware and configuration
files, maintained for research and preservation purposes. It is not affiliated
with, endorsed by, or sponsored by Cowboy.

These files were obtained through temporary access to Cowboy's Backoffice
application, which was granted to me directly by Cowboy support. No
authentication was bypassed and no protected systems were accessed.

If you represent Cowboy and would like this content removed, please reach out
to **me@jimweb.eu** and I'll take it down promptly.

## Contact

- **Email:** [me@jimweb.eu](mailto:me@jimweb.eu)
- **Website:** [jimweb.eu](https://jimweb.eu)

## Firmware availability

| Model             | Cockpit firmware | Main firmware &nbsp;·&nbsp; deployed → frozen |
| :---------------- | :--------------: | :-------------------------------------------- |
| Cowboy 1          |        —         | `dfu-fw` v3.3.1 → v3.3.1                      |
| Cowboy 1+         |        —         | `sdblapp` v4.8.17 → v4.8.14                   |
| Cowboy 2          |        —         | `A2-app` v4.21.5 → `app` v4.6.5 <sup>†</sup>  |
| Cowboy 3          |        —         | `A2-app` v4.21.5 → v4.9.3                     |
| Classic           |      v2.3.0      | `A4-app` v4.21.5 → v4.21.10                   |
| Classic (US)      |      v2.3.0      | `A4-app` v4.21.5 → v4.12.1                    |
| Cruiser           |      v2.3.0      | `A4-app` v4.21.5 → v4.21.10                   |
| Cruiser ST        |      v2.3.0      | `A4-app` v4.21.5 → v4.21.10                   |
| Cruiser ST (US)   |      v2.3.0      | `A4-app` v4.21.5 → v4.19.12                   |
| Cross             |        —         | `A4-app` v4.21.5 → v4.21.10                   |
| Cross ST          |        —         | `A4-app` v4.21.5 → v4.21.10                   |

## Files per model

<details>
<summary><b>Cowboy 1</b></summary>

```
firmware/
├── deployed/  dfu-fw-release-v3.3.1_deployed.zip
└── frozen/    dfu-fw-release-v3.3.1_frozen.zip
```
</details>

<details>
<summary><b>Cowboy 1+</b></summary>

```
firmware/
├── deployed/  CowboyFW_A1_5-sdblapp-release-v4.8.17_deployed.zip
└── frozen/    CowboyFW_A1_5-sdblapp-release-v4.8.14_frozen.zip
```
</details>

<details>
<summary><b>Cowboy 2</b></summary>

```
firmware/
├── deployed/  CowboyFW_A2-app-release-v4.21.5_deployed.zip
└── frozen/    CowboyFW-app-release-v4.6.5_frozen.zip
```
</details>

<details>
<summary><b>Cowboy 3</b></summary>

```
firmware/
├── deployed/  CowboyFW_A2-app-release-v4.21.5_deployed.zip
└── frozen/    CowboyFW_A2-app-release-v4.9.3_frozen.zip
```
</details>

<details>
<summary><b>Classic</b></summary>

```
cockpit/
├── deployed/  CockpitFW_app_v2.3.0_deployed.bin
└── frozen/    CockpitFW_app_v2.3.0_frozen.bin
firmware/
├── deployed/  CowboyFW_A4-app-release-v4.21.5_deployed.zip
└── frozen/    CowboyFW_A4-app-release-v4.21.10_frozen.zip
```
</details>

<details>
<summary><b>Classic (US)</b></summary>

```
cockpit/
├── deployed/  CockpitFW_app_v2.3.0_deployed.bin
└── frozen/    CockpitFW_app_v2.3.0_frozen.bin
firmware/
├── deployed/  CowboyFW_A4-app-release-v4.21.5_deployed.zip
└── frozen/    CowboyFW_A4-app-release-v4.12.1_frozen.zip
```
</details>

<details>
<summary><b>Cruiser</b></summary>

```
cockpit/
├── deployed/  CockpitFW_app_v2.3.0_deployed.bin
└── frozen/    CockpitFW_app_v2.3.0_frozen.bin
firmware/
├── deployed/  CowboyFW_A4-app-release-v4.21.5_deployed.zip CowboyFW_A4-app-release-v4.22.7_deployed.zip
└── frozen/    CowboyFW_A4-app-release-v4.21.10_frozen.zip
```
</details>

<details>
<summary><b>Cruiser ST</b></summary>

```
cockpit/
├── deployed/  CockpitFW_app_v2.3.0_deployed.bin
└── frozen/    CockpitFW_app_v2.3.0_frozen.bin
firmware/
├── deployed/  CowboyFW_A4-app-release-v4.21.5_deployed.zip CowboyFW_A4-app-release-v4.22.7_deployed.zip
└── frozen/    CowboyFW_A4-app-release-v4.21.10_frozen.zip
```
</details>

<details>
<summary><b>Cruiser ST (US)</b></summary>

```
cockpit/
├── deployed/  CockpitFW_app_v2.3.0_deployed.bin
└── frozen/    CockpitFW_app_v2.3.0_frozen.bin
firmware/
├── deployed/  CowboyFW_A4-app-release-v4.21.5_deployed.zip CowboyFW_A4-app-release-v4.22.7_deployed.zip
└── frozen/    CowboyFW_A4-app-release-v4.19.12_frozen.zip
```
</details>

<details>
<summary><b>Cross</b></summary>

```
firmware/
├── deployed/  CowboyFW_A4-app-release-v4.21.5_deployed.zip
└── frozen/    CowboyFW_A4-app-release-v4.21.10_frozen.zip
```
</details>

<details>
<summary><b>Cross ST</b></summary>

```
firmware/
├── deployed/  CowboyFW_A4-app-release-v4.21.5_deployed.zip
└── frozen/    CowboyFW_A4-app-release-v4.21.10_frozen.zip
```
</details>

---

Each model has its own controller configuration too. If it's missing, then I couldn't parse it.
Feel free to contribute :)
