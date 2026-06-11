# wfx-fullMAC-driver license layout

This package bundles two differently-licensed components:

| Path | License |
|---|---|
| `wfx_fmac_driver/**` (driver sources, default) | **Apache-2.0** (per the LICENSE file in the upstream `SiliconLabs/wfx-fullMAC-driver` repository; each source file carries the Apache-2.0 header) |
| `wfx_fmac_driver/firmware/sl_wfx_wf200_C0.h` | **Silicon Labs Limited Redistribution and Use License** (`LicenseRef-Silabs-LRL`) |

`sl_wfx_wf200_C0.h` is the WF200 firmware blob (a C array of the binary
image). The Limited Redistribution and Use License permits redistribution in
binary form **without modification**; reverse engineering, decompilation, and
disassembly are prohibited. The full license text is embedded at the top of
that file — see the header comment of
`wfx_fmac_driver/firmware/sl_wfx_wf200_C0.h`.

The combined SPDX expression for the package is
`Apache-2.0 AND LicenseRef-Silabs-LRL` (see `package.json`).

The wrapper files themselves (`package.json`, `README.md`, this file) are
Apache-2.0.
