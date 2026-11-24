# CMP Pogo

**3D-printable pogo-pin jig for NVIDIA CMP 170HX voltage-glitching experiments.**

CMP Pogo is a 3D-printable fixture designed to help align and hold pogo-pin contacts on the NVIDIA CMP 170HX, with a separate bracket for a Raspberry Pi Pico controller. It is intended for electronics enthusiasts and hardware researchers working on their own equipment.
<img width="3024" height="3024" alt="cmp-pogo-unwired" src="https://github.com/user-attachments/assets/d5d4cffa-dc40-4912-9551-40930ed3ccd3" />
<img width="3024" height="3024" alt="cmp-pogo-wired" src="https://github.com/user-attachments/assets/7d793c7b-9538-49bf-9fa9-58f8905e9ada" />
<img width="3024" height="3024" alt="cmp-pogo-installed" src="https://github.com/user-attachments/assets/1a554700-2756-43ab-afba-409479d45383" />
<p align="center">
  <img src="https://github.com/user-attachments/assets/d5d4cffa-dc40-4912-9551-40930ed3ccd3" width="32%" alt="CMP Pogo - Unwired">
  <img src="https://github.com/user-attachments/assets/7d793c7b-9538-49bf-9fa9-58f8905e9ada" width="32%" alt="CMP Pogo - Wired">
  <img src="https://github.com/user-attachments/assets/1a554700-2756-43ab-afba-409479d45383" width="32%" alt="CMP Pogo - Installed">
</p>
> **Project status:** Initial documentation. The printable STL files and detailed assembly guide will be added separately. The kit is supplied unassembled.

## Download STL Files

The project uses three 3D-printed components:

| File | Purpose |
| --- | --- |
| `Base.stl` | Main holder that positions the pogo pins over the GPU contact points. |
| `Case.stl` | Mounting bracket for the Raspberry Pi Pico. |
| `Wase.stl` | Spacer that slightly raises the Base above the GPU; the physical kit includes eight of these spacers. |

**STL downloads are not available yet.** The final files will be placed in the [STL directory](STL/) once uploaded. Please do not use screenshots or recreated models as printable substitutes.

These models are provided for **noncommercial use** under the [CC BY-NC-ND 4.0 license](LICENSE). You may print copies for your own noncommercial use, but commercial use and public distribution of modified models are not licensed. See [License](#contributing--license) for details.

## Get the Physical Kit

If you would rather receive the 3D-printed parts and accessories together, a physical CMP Pogo kit is available to order:

**[Buy the CMP Pogo Kit on PayPal](https://www.paypal.com/ncp/payment/VH5EUH9KT26WW)**

The physical kit includes:

- 1× **Base** — main pogo-pin holder
- 1× **Case** — Raspberry Pi Pico mounting bracket
- 8× **Wase** — support spacers
- 10× **female-to-female Dupont jumper wires** (10 cm): 5 with pogo pins pre-inserted and 5 without pogo pins
- 5× **additional loose pogo pins**
- 4× **M2.5 × 16 mm Torx T8 screws**

The Raspberry Pi Pico and the NVIDIA CMP 170HX GPU are **not included**. The kit is supplied **unassembled**. Consult the PayPal checkout for the current price and ordering details.

## How It Works

The **Base** holds and guides pogo pins so they can make contact with selected points on the CMP 170HX PCB. **Wase** spacers sit between the Base and GPU to provide clearance; the screws secure the fixture. The separate **Case** is designed to hold the Raspberry Pi Pico controller. **Dupont jumper wires** provide the connections between the contacts and the controller.

CMP Pogo is a *mechanical positioning aid*, not an automatic GPU-unlocking device. Successful experiments depend on the user's setup and procedure; no particular result is guaranteed.

> **Hardware safety:** Incorrect contact placement, wiring, or use can damage equipment. Verify the fit, electrical connections, and applicable documentation before use.

## Assembly Guide

**Coming soon.** A step-by-step assembly guide, including orientation and installation details, is planned for a future update.

## Contributing & License

Found a possible improvement? Please [open an issue](../../issues) first to explain your suggestion. Pull requests can be considered under the limited contribution permission and rights-grant process described in [CONTRIBUTING.md](CONTRIBUTING.md).

Unless otherwise stated, the project’s original STL designs and documentation are licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/). See [LICENSE](LICENSE).

The license does **not** grant commercial rights or the right to publicly distribute adapted STL designs. Permission for commercial uses or distribution of modified versions must be requested separately from the project owner. Any special permission to submit a contribution is limited to that submission process.

*This project is independent and is not affiliated with or endorsed by NVIDIA, Raspberry Pi, or any other hardware manufacturer.*
