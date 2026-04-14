PotatoPi
Overview

PotatoPi is a custom RP2040-based devboard that can be used for lots of cool hardware and software projects.
It follows the same pinout as the Raspberry Pi Pico and is fully feature-compatible.

It will also include headers soldered on.

- Features
- 16MB onboard flash memory
- Convenient reset button for easy flashing
- Custom PotatoPi artwork on both sides of the PCB
- All components hand soldered (no PCBA)

I made this to get back into hardware and to redeem myself from my last project.
I also wanted to try out SMD soldering.

Gallery

Front & board renders as well as Potato Pi illustrations:

<p float="left"> <img width="356" height="651" alt="Screenshot 2026-04-14 102804" src="https://github.com/user-attachments/assets/7c3f891a-bb0d-4e7e-83cc-8c3f2b0e18fb" /> <img src="https://github.com/user-attachments/assets/2c9f7826-c926-43a8-a755-8cab63f8067b" /> <img src="https://github.com/user-attachments/assets/0d66416b-50a1-4beb-a662-bbd869390431" /> </p> <p float="left"> <img src="https://github.com/user-attachments/assets/024346d4-5a19-431f-8776-90b8332c3d5f" width="300"/> <img src="https://github.com/user-attachments/assets/e092c213-ff30-4260-bfb4-da09e4d3f89b" width="300"/> <img src="https://github.com/user-attachments/assets/ac1637eb-51a1-498f-8126-9a3e58c35e30" width="300"/> <img src="https://github.com/user-attachments/assets/10679dad-0d70-415a-b012-5a2db32e9d90" width="300"/> </p>

Bill of Materials (BOM)

| **Category** | **Designator / Item** | **Footprint / Description** | **Qty** | **Value / Part** | **Link**                                                                                                 | **Cost** |
| ------------ | --------------------- | --------------------------- | ------- | ---------------- | -------------------------------------------------------------------------------------------------------- | -------- |
| Capacitor    | C1, C12               | 402                         | 2       | 1µF              | [https://www.lcsc.com/product-detail/C29266.html](https://www.lcsc.com/product-detail/C29266.html)       | 0.26     |
| Capacitor    | C10–C11, C17, C2–C9   | 402                         | 11      | 0.1µF            | [https://www.lcsc.com/product-detail/C1525.html](https://www.lcsc.com/product-detail/C1525.html)         | 0.13     |
| Capacitor    | C13, C14              | 603                         | 2       | 10µF             | [https://www.lcsc.com/product-detail/C19702.html](https://www.lcsc.com/product-detail/C19702.html)       | 0.40     |
| Capacitor    | C15, C16              | 603                         | 2       | 33pF             | [https://www.lcsc.com/product-detail/C107047.html](https://www.lcsc.com/product-detail/C107047.html)     | 0.30     |
| Connector    | J1                    | USB-C Receptacle            | 1       | USB 2.0 14P      | [https://www.lcsc.com/product-detail/C165948.html](https://www.lcsc.com/product-detail/C165948.html)     | 0.85     |
| Connector    | J2, J3                | Pin Header 1x20             | 2       | Conn_01x20       | [https://www.lcsc.com/product-detail/C42431804.html](https://www.lcsc.com/product-detail/C42431804.html) | 0.46     |
| Connector    | J4                    | Pin Header 1x03             | 1       | Conn_01x03       | [https://www.lcsc.com/product-detail/C32713269.html](https://www.lcsc.com/product-detail/C32713269.html) | 0.11     |
| Resistor     | R1, R2                | 402                         | 2       | 5.1kΩ            | [https://www.lcsc.com/product-detail/C25905.html](https://www.lcsc.com/product-detail/C25905.html)       | 0.08     |
| Resistor     | R3, R4                | 402                         | 2       | 27Ω              | [https://www.lcsc.com/product-detail/C25100.html](https://www.lcsc.com/product-detail/C25100.html)       | 0.08     |
| Resistor     | R5, R6                | 402                         | 2       | 1kΩ              | [https://www.lcsc.com/product-detail/C11702.html](https://www.lcsc.com/product-detail/C11702.html)       | 0.07     |
| Resistor     | R7                    | 402                         | 1       | 10kΩ             | [https://www.lcsc.com/product-detail/C60490.html](https://www.lcsc.com/product-detail/C60490.html)       | 0.08     |
| Switch       | SW1                   | Push Button                 | 1       | Momentary        | [https://www.lcsc.com/product-detail/C720477.html](https://www.lcsc.com/product-detail/C720477.html)     | 0.55     |
| IC           | U1                    | QFN-56                      | 1       | RP2040           | [https://www.lcsc.com/product-detail/C2040.html](https://www.lcsc.com/product-detail/C2040.html)         | 0.95     |
| IC           | U2                    | SOT-23                      | 1       | MCP1700-3302     | [https://www.lcsc.com/product-detail/C39051.html](https://www.lcsc.com/product-detail/C39051.html)       | 2.45     |
| IC           | U3                    | USON-8                      | 1       | W25Q16JV         | [https://www.lcsc.com/product-detail/C2456208.html](https://www.lcsc.com/product-detail/C2456208.html)   | 1.31     |
| Crystal      | Y1                    | 3225                        | 1       | 12 MHz           | [https://www.lcsc.com/product-detail/C9002.html](https://www.lcsc.com/product-detail/C9002.html)         | 0.73     |
| Service      | PCB                   | JLCPCB fabrication          | 1       | Manufacturing    | [https://cart.jlcpcb.com/quote/gerberviewThree/?qs=d00311a2c2824fc7aa7ee1bc072ff726_1_0_1_0_0.html]                                                                                                     | 2.10     |
| Tool         | Tip                   | T18-D24 solder tip          | 1       | Hakko chisel     | [https://www.microcenter.com/product/658966/hakko-t18-series-006-in-chisel-tip]                                                                                            | 6.99     |
| Tool         | Wick                  | Desolder wick               | 1       | iFixit wick      |[https://www.microcenter.com/product/693022/ifixit-desoldering-wick]                                                                                            | 4.99     |
| Tool         | Tweezers              | Curved ESD                  | 1       | precision        | [https://www.microcenter.com/product/361636/enkay-products-heat-resistant-soldering-tweezers-curved-point]                                                                                             | 2.99     |
| Tool         | Helping Hand          | Magnifier stand             | 1       | third hand       |[https://www.microcenter.com/product/618902/inland-inland-adjustable-helping-hand-w-magnifying-glass]                                                                                             | 4.99     |
Cost Summary
Subtotal: $30.87
Shipping: $15.24
Tax: $3.82
TOTAL: $49.93
