# Harmony 3 BSP module

This module contains the definitions of all development kits (A.K.A boards) supported by Harmony 3.

- [PIC32MK GP Development Kit](boards/pic32mk_gp_db/readme.md)
- [SAM E70 Xplained](boards/sam_e70_xpld/readme.md)
- [SAM 9X60 Evaluation Kit](boards/sam_9x60_ek/readme.md)
- [SAM A5D2 Xplained Ultra](boards/sam_a5d2_xult/readme.md)

<!-- yaml
---
module:
  name: "BSP"
  id: "B588CB7D-61DC-47D2-AED3-83225E3F62C8"
  version: "3.5.0"
  type: "bsp"

  configroot:
    path: "config/module.py"

  boards:
    - name: "PIC32MX274 XLP Starter Kit"
      processor: "PIC32MX274F256D"
      config: "pic32mx_xlp_sk"

    - name: "PIC32MX1/2/5 Starter Kit"
      processor: "PIC32MX570F512L"
      config: "pic32mx_125_sk"

    - name: "PIC32MX1XX/2XX Starter Kit"
      processor: "PIC32MX250F128D"
      config: "pic32mx_12_sk"

    - name: "PIC32MX USB Starter Kit III"
      processor: "PIC32MX450F256L"
      config: "pic32mx_usb_sk3"

    - name: "PIC32MX Ethernet Starter Kit II"
      processor: "PIC32MX795F512L"
      config: "pic32mx_eth_sk2"

    - name: "PIC32MX Bluetooth Audio Development Kit"
      processor: "PIC32MX270F512L"
      config: "pic32mx_btadk"

    - name: "PIC32MX Bluetooth Audio Development Kit"
      processor: "PIC32MX470F512L"
      config: "pic32mx_btadk"

    - name: "PIC32MZ EF Bluetooth Audio Development Kit"
      processor: "PIC32MZ2048EFH144"
      config: "pic32mz_ef_btadk"

    - name: "PIC32MK GP Development Kit"
      processor: "PIC32MK1024GPE100"
      config: "pic32mk_gp_db"

    - name: "PIC32MK MCJ Curiosity Pro"
      processor: "PIC32MK0512MCJ064"
      config: "pic32mk_mcj_curiosity_pro"

    - name: "PIC32MK GPL Curiosity Pro"
      processor: "PIC32MK1024GPL100"
      config: "pic32mk_gpl_curiosity_pro"

    - name: "PIC32MX470 Curiosity Development Board"
      processor: "PIC32MX470F512H"
      config: "pic32mx470_curiosity"

    - name: "PIC32MZ DA Starter Kit"
      processor: "PIC32MZ2064DAG169"
      config: "pic32mz_da_sk"

    - name: "PIC32MZ DA Starter Kit"
      processor: "PIC32MZ2064DAH169"
      config: "pic32mz_da_sk"

    - name: "PIC32MZ DA Starter Kit"
      processor: "PIC32MZ2064DAR169"
      config: "pic32mz_da_sk"

    - name: "PIC32MZ DA Starter Kit"
      processor: "PIC32MZ2064DAS169"
      config: "pic32mz_da_sk"

    - name: "PIC32MZ DA Starter Kit"
      processor: "PIC32MZ2064DAA288"
      config: "pic32mz_da_sk"

    - name: "PIC32MZ DA Starter Kit"
      processor: "PIC32MZ2064DAB288"
      config: "pic32mz_da_sk"

    - name: "PIC32MZ EF Starter Kit"
      processor: "PIC32MZ2048EFH144"
      config: "pic32mz_ef_sk"

    - name: "PIC32MZ EF Starter Kit"
      processor: "PIC32MZ2048EFM144"
      config: "pic32mz_ef_sk"

    - name: "PIC32MZ EF Curiosity 2.0"
      processor: "PIC32MZ2048EFM144"
      config: "pic32mz_ef_curiosity_v2"

    - name: "SAM 9X60 Evaluation Kit"
      processor: "SAM9X60"
      config: "sam_9x60_ek"

    - name: "SAM A5D2 Xplained Ultra"
      processor: "ATSAMA5D27"
      config: "sam_a5d2_xult"

    - name: "SAM C21 Xplained Pro"
      processor: "ATSAMC21J18A"
      config: "sam_c21_xpro"

    - name: "SAM C21N Xplained Pro"
      processor: "ATSAMC21N18A"
      config: "sam_c21n_xpro"

    - name: "SAM D10 Xplained Mini"
      processor: "ATSAMD10D14AM"
      config: "sam_d10_xmini"

    - name: "SAM D11 Xplained Pro"
      processor: "ATSAMD11D14AM"
      config: "sam_d11_xpro"

    - name: "SAM D20 Xplained Pro"
      processor: "ATSAMD20J18"
      config: "sam_d20_xpro"

    - name: "SAM D21 Xplained Pro"
      processor: "ATSAMD21J18A"
      config: "sam_d21_xpro"

    - name: "SAM DA1 Xplained Pro"
      processor: "ATSAMDA1J16B"
      config: "sam_da1_xpro"

    - name: "SAM L10 Xplained Pro"
      processor: "ATSAML10E16A"
      config: "sam_l10_xpro"

    - name: "SAM E54 Xplained Pro"
      processor: "ATSAME54P20A"
      config: "sam_e54_xpro"

    - name: "SAM G55 Xplained Pro"
      processor: "ATSAMG55J19"
      config: "sam_g55_xpro"

    - name: "SAM E54 Curiosity Ultra"
      processor: "ATSAME54P20A"
      config: "sam_e54_cult"

    - name: "SAM E70 Xplained"
      processor: "ATSAME70Q21B"
      config: "sam_e70_xpld"

    - name: "SAM E70 Xplained Ultra"
      processor: "ATSAME70Q21B"
      config: "sam_e70_xult"

    - name: "SAM L21 Xplained Pro"
      processor: "ATSAML21J18B"
      config: "sam_l21_xpro"

    - name: "SAM L22 Xplained Pro"
      processor: "ATSAML22N18A"
      config: "sam_l22_xpro"

    - name: "SAM RH71 Evaluation Kit"
      processor: "ATSAMRH71F20B"
      config: "sam_rh71_ek"

    - name: "SAM V71 Xplained Ultra"
      processor: "ATSAMV71Q21B"
      config: "sam_v71_xult"
---
-->