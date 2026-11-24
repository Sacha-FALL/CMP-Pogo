# CMP Pogo

**3D-printable pogo-pin jig for NVIDIA CMP 170HX voltage-glitching experiments.**

CMP Pogo is a 3D-printable fixture designed to help align and hold pogo-pin contacts on the NVIDIA CMP 170HX, with a separate bracket for a Raspberry Pi Pico controller. It is intended for electronics enthusiasts and hardware researchers working on their own equipment.
<p align="center">
  <a href="#download-stl-files"><img src="https://img.shields.io/badge/Download_STL-238636?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNmZmYiIHN0cm9rZS13aWR0aD0iMi4yIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xMiAzdjEybS01LTUgNSA1IDUtNU00IDE2djRoMTZ2LTQiLz48L3N2Zz4%3D" alt="Download STL files"></a>
  <a href="https://www.paypal.com/ncp/payment/VH5EUH9KT26WW"><img src="https://img.shields.io/badge/Buy_the_Kit-003087?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNmZmYiIHN0cm9rZS13aWR0aD0iMi4yIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0yIDNoM2wzIDEzaDEybDItMTBINiIvPjxjaXJjbGUgY3g9IjkiIGN5PSIyMSIgcj0iMSIvPjxjaXJjbGUgY3g9IjE5IiBjeT0iMjEiIHI9IjEiLz48L3N2Zz4%3D" alt="Buy the CMP Pogo kit"></a>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d5d4cffa-dc40-4912-9551-40930ed3ccd3" width="32%" alt="CMP Pogo - Unwired">
  <img src="https://github.com/user-attachments/assets/7d793c7b-9538-49bf-9fa9-58f8905e9ada" width="32%" alt="CMP Pogo - Wired">
  <img src="https://github.com/user-attachments/assets/1a554700-2756-43ab-afba-409479d45383" width="32%" alt="CMP Pogo - Installed">
</p>

> **Project status:** Initial documentation. The printable STL files are available. Detailed assembly guide will be added later.

## Download STL Files

The project uses three 3D-printed components:

| File | Purpose |
| --- | --- |
| `Base.stl` | Main holder that positions the pogo pins over the GPU contact points. |
| `Case.stl` | Mounting bracket for the Raspberry Pi Pico. |
| `Wase.stl` | Spacer that slightly raises the Base above the GPU. |

 <a href="#download-stl-files"><img src="https://img.shields.io/badge/Download_STL-238636?style=for-the-badge&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNmZmYiIHN0cm9rZS13aWR0aD0iMi4yIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik0xMiAzdjEybS01LTUgNSA1IDUtNU00IDE2djRoMTZ2LTQiLz48L3N2Zz4%3D" alt="Download STL files"></a>
 
**STL downloads are not available yet.** The final files will be placed in the [3D Parts directory](3D%20Parts/) once uploaded.

The original CMP Pogo designs (`Base.stl` and `Wase.stl`) are provided for **noncommercial use** under the [CC BY-NC-ND 4.0 license](LICENSE).

`Case.stl` is based on the [Raspberry Pi Pico Case](https://www.printables.com/model/143745-raspberry-pi-pico-case) by **GrevTech**, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), and has been modified for CMP Pogo.

## Get the Physical Kit

If you would rather receive the 3D-printed parts and accessories together, a physical CMP Pogo kit is available to order:

[![Buy the CMP Pogo Kit on PayPal](https://img.shields.io/badge/PayPal-Buy_the_Kit-003087?style=for-the-badge&logo=paypal&logoColor=white&labelColor=005EA6)](https://www.paypal.com/ncp/payment/VH5EUH9KT26WW)

The physical kit includes:

- 1× **Base** — main pogo-pin holder
- 1× **Case** — Raspberry Pi Pico mounting bracket
- 8× **Wase** — support spacers
- 10× **Dupont jumper wires** (10 cm): 5 with pogo pins pre-inserted and 5 without pogo pins
- 5× **additional loose pogo pins**
- 4× **M2.5 × 16 mm Torx T8 screws**

Consult the PayPal checkout for the current price and ordering details.

## How It Works

The **Base** holds and guides pogo pins so they can make contact with selected points on the CMP 170HX PCB. **Wase** spacers sit between the Base and GPU to provide clearance; the screws secure the fixture. The separate **Case** is designed to hold the Raspberry Pi Pico controller. **Dupont jumper wires** provide the connections between the contacts and the controller.

> **Hardware safety:** Incorrect contact placement, wiring, or use can damage equipment. Verify the fit, electrical connections, and applicable documentation before use.

## Assembly Guide

**Coming soon.** A step-by-step assembly guide, including orientation and installation details, is planned for a future update.

## Contributing & License

Found a possible improvement? Please [open an issue](../../issues) first to explain your suggestion. Pull requests can be considered under the limited contribution permission and rights-grant process described in [CONTRIBUTING.md](CONTRIBUTING.md).

The original CMP Pogo designs (`Base.stl` and `Wase.stl`) and original documentation are licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/). See [LICENSE](LICENSE).

The CC BY-NC-ND license does **not** grant commercial rights or the right to publicly distribute adaptations of the material it covers. Permission for commercial uses or distribution of modified versions must be requested separately from the project owner. Any special permission to submit a contribution is limited to that submission process.
