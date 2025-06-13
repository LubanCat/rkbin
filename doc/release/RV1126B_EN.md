# rv1126b Release Note

## rv1126b_bl31_v1.07.elf

| Date       | File                  | Build commit | Severity  |
| ---------- | :-------------------- | ------------ | --------- |
| 2025-06-13 | rv1126b_bl31_v1.07.elf | 46bfa4121 | important |

### New

1. Save/restore PVTPLL when system suspend/resume.
2. Improve stability of system reboot.
3. Support to boot HPMCU.
4. Improve stability of system temperature control.

------

## rv1126b{p}_ddr_{1332, 1056}MHz_v1.03.bin

| Date       | File                                     | Build commit | Severity |
| ---------- | :--------------------------------------- | ------------ | -------- |
| 2025-06-13 | rv1126b{p}_ddr_{1332, 1056}MHz_v1.03.bin | c4d8224017   | critical |

### Warn

1. The bl31 should be updated to v1.06 or above.

### Fixed

| Index | Severity  | Update                    | Issue description                                            | Issue source |
| ----- | --------- | ------------------------- | ------------------------------------------------------------ | ------------ |
| 1     | important | Fix refresh_margin        | LPDDR4(X) and LPDDR3 may be unstable at elevated temperatures and low frequencies | -            |
| 2     | critical  | Fix DDR4 stability issues |                                                              | -            |

------

## rv1126b_bl31_v1.06.elf

| Date       | File                  | Build commit | Severity  |
| ---------- | :-------------------- | ------------ | --------- |
| 2025-06-06 | rv1126b_bl31_v1.06.elf | 1b7f2f7db | important |

### New

1. Improve the speed of system suspend/resume.
2. Enhance the stability of system suspend/resume for DDR4 boards.

------

## rv1126b_hpmcu_tb_v1.00.bin

| Date       | File                  | Build commit | Severity |
| ---------- | :-------------------- | ----------- | -------- |
| 2025-05-27 | rv1126b_hpmcu_tb_v1.00.bin | rtt:3377af5ff6#hal:5c682f97 | important |

### New

1. Initial version.

------

## rv1126b_bl31_v1.05.elf

| Date       | File                  | Build commit | Severity  |
| ---------- | :-------------------- | ------------ | --------- |
| 2025-05-16 | rv1126b_bl31_v1.05.elf | ce0a773ac | important |

### New

1. Support fiq-debugger.
2. Support lp_pr sleep mode.

------

## rv1126b_bl32_v1.03.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-05-12 | rv1126b_bl32_v1.03.bin | 6fa7d182f    | important |

### Fixed

| Index | Severity  | Update                                                   | Issue description | Issue source |
| ----- | --------- | -------------------------------------------------------- | ----------------- | ------------ |
| 1     | important | fix crypto result error when using dynamic shared memory | -                 | -            |

------

## rv1126b_usbplug_v1.03.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-05-13 | rv1126b_usbplug_v1.03.bin | 37d8770ee4   | important |

### New

1. Fix reboot fail.

------

## rv1126b_usbplug_v1.02.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-05-09 | rv1126b_usbplug_v1.02.bin | ac302d626c    | important |

### New

1. Add uart upgrade support.

------

## rv1126b_spl{, _ipc}_v1.03.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-05-08 | rv1126b_spl{, _ipc}_v1.03.bin | bc03ef0985f    | important |

### New

1. Fix bias error.

------

## rv1126b_bl31_v1.04.elf

| Date       | File                  | Build commit | Severity  |
| ---------- | :-------------------- | ------------ | --------- |
| 2025-05-06 | rv1126b_bl31_v1.04.elf | 886a0421f | important |

### New

1. Support LP_AOA sleep mode.
2. Support non-secure configuration remap_dsmc, remap_perixip, remap_pmuxip.
3. Enable tsadc_shut_m0 function.

------

## rv1126b_spl{, _ipc}_v1.02.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-05-06 | rv1126b_spl{, _ipc}_v1.02.bin | e4069c1b773    | important |

### New

1. Adjust tsadc bias current.

------

## rv1126b{p}_ddr_{1332, 1056}MHz_v1.02.bin

| Date       | File                                     | Build commit | Severity |
| ---------- | :--------------------------------------- | ------------ | -------- |
| 2025-04-25 | rv1126b{p}_ddr_{1332, 1056}MHz_v1.02.bin | 701e251084   | critical |

### New

1. Added support for arch timer 1GHz.
2. Added thunder-boot DDR bin.
3. Added eyescan DDR bin.

### Fixed

| Index | Severity  | Update                                                       | Issue description             | Issue source |
| ----- | --------- | ------------------------------------------------------------ | ----------------------------- | ------------ |
| 1     | important | Optimized SI configuration                                   | -                             | -            |
| 2     | critical  | Fix clk skew calculation error in certain scenarios          | Instability in some DDR3/DDR4 | -            |
| 3     | critical  | Fix LPDDR4(X) stability issues                               | -                             | -            |
| 4     | critical  | Resolve initialization failures for specific memory capacity combinations | -                             | -            |

------

## rv1126b_bl32_v1.02.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-04-23 | rv1126b_bl32_v1.02.bin | 106240c23    | important |

### Fixed

| Index | Severity  | Update                                  | Issue description | Issue source |
| ----- | --------- | --------------------------------------- | ----------------- | ------------ |
| 1     | important | correct whether reading ns otp with ecc | -                 | -            |

------

## rv1126b_bl31_v1.03.elf

| Date       | File                  | Build commit | Severity  |
| ---------- | :-------------------- | ------------ | --------- |
| 2025-04-16 | rv1126b_bl31_v1.03.elf | d93a2fceb | important |

### New

1. Improve stability of system suspend .

------

## rv1126b_bl31_v1.02.elf

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-04-15 | rv1126b_bl31_v1.02.elf | 32ea6e285    | important |

### New

1. BL31 runs at 0x40000000.
2. Save/restore data of system sram when system suspend/resume.

------

## rv1126b_spl_v1.01.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-04-14 | rv1126b_spl_v1.01.bin | 8532419ba16    | important |

### New

1. Add arch timer 1Ghz support.

------

## rv1126b_usbplug_v1.01.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-04-14 | rv1126b_usbplug_v1.01.bin | 8532419ba16    | important |

### New

1. Add arch timer 1Ghz support.

------

## rv1126b_bl32_v1.01.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-04-14 | rv1126b_bl32_v1.01.bin | 0e8447122    | important |

### New

1. Add support for oem otp key cipher.

### Fixed

| Index | Severity  | Update                          | Issue description | Issue source |
| ----- | --------- | ------------------------------- | ----------------- | ------------ |
| 1     | important | fixed FW Enryption Key offset   | -                 | -            |
| 2     | important | correct the clock used by RKRNG | -                 | -            |

------

## rv1126b_bl32_v1.00.bin

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-04-08 | rv1126b_bl32_v1.00.bin | f63ac68db    | important |

### New

1. Initial version.

------

## rv1126b_bl31_v1.01.elf

| Date       | File                   | Build commit | Severity  |
| ---------- | :--------------------- | ------------ | --------- |
| 2025-04-02 | rv1126b_bl31_v1.01.elf | a14bf51f4    | important |

### New

1. Support system suspend.
2. Support scmi clock.

------

## rv1126b_{ddr,spl,usbplug,bl31}_v1.00.bin

| Date       | File                                     | Build commit                                                 | Severity |
| ---------- | :--------------------------------------- | ------------------------------------------------------------ | -------- |
| 2025-03-31 | rv1126b_{ddr,spl,usbplug,bl31}_v1.00.bin | ddr:cca56bbb07#spl:4d9e803d493#usbplug:4d9e803d493#bl31:a2173dab6 | moderate |

### New

1. Initial version.

------

