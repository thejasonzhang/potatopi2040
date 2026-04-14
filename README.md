PotatoPi
<br>
PotatoPi is an custom RP2040-based devboard that can be used for lots of cool hardware and software projects. It follows the same pinout as the Raspberry Pi Pico and is fully feature-compatible.
It will also include headers soldered on.

It includes:

16MB of onboard flash memory
A convenient reset button for easy flashing
Custom PotatoPi artwork on both sides of the PCB

All components will be hand soldered (no PCBA).

I made this to get back into hardware and to redeem myself from my last project. 
I also wanted to try out SMD soldering.

Gallery
Front & Board Renders as well as Potato Pi Illustrations
<p float="left"> 
<img width="356" height="651" alt="Screenshot 2026-04-14 102804" src="https://github.com/user-attachments/assets/7c3f891a-bb0d-4e7e-83cc-8c3f2b0e18fb" />
<img src="https://github.com/user-attachments/assets/2c9f7826-c926-43a8-a755-8cab63f8067b" />
<img src="https://github.com/user-attachments/assets/0d66416b-50a1-4beb-a662-bbd869390431" />
</p> <p float="left"> <img src="https://github.com/user-attachments/assets/024346d4-5a19-431f-8776-90b8332c3d5f" width="300"/> <img src="https://github.com/user-attachments/assets/e092c213-ff30-4260-bfb4-da09e4d3f89b" width="300"/> <img src="https://github.com/user-attachments/assets/ac1637eb-51a1-498f-8126-9a3e58c35e30" width="300"/> <img src="https://github.com/user-attachments/assets/10679dad-0d70-415a-b012-5a2db32e9d90" width="300"/> </p>

BOM (you can find this as a separate file too)
Designator,Footprint,Quantity,Value,link,Unir Cost,Cost,Column 1
"C1, C12",402,2,1uF,https://www.lcsc.com/product-detail/C29266.html?s_z=n_1uF&spm=wm.ssy.bg.4.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVlJURllaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.0026*100=0.26,0.26,TRUE
"C10, C11, C17, C2, C3, C4, C5, C6, C7, C8, C9",402,11,0.1uF,https://www.lcsc.com/product-detail/C1525.html?s_z=n_CL05B104KO5NNNC&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVlFRQVNcUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4eFQsCAgIaSgADAwAHC0slQ1dYX1ZeT1NADxALGw%3D%3D,0.0013*100=0.13,0.13,TRUE
"C13, C14",603,2,10uF,https://www.lcsc.com/product-detail/C19702.html?s_z=n_10uF&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVldeRVBYVDsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.008*50=0.4,0.4,TRUE
"C15, C16",603,2,33pF,https://www.lcsc.com/product-detail/C107047.html?s_z=n_33pF&spm=wm.ssy.bg.2.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVlZXR1BeUTsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.003*100=0.3,0.3,TRUE
J1,USB_C_Receptacle_HRO_TYPE-C-31-M-12,1,USB_C_Receptacle_USB2.0_14P,https://www.lcsc.com/product-detail/C165948.html?s_z=n_TYPE-C-31-M-12&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVlVVR1lfUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.17*5=0.85,0.85,TRUE
"J2, J3",PinHeader_1x20_P2.54mm_Vertical,2,Conn_01x20,https://www.lcsc.com/product-detail/C42431804.html?s_z=n_1x20&spm=wm.ssy.bg.1.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVVJVQ1hXVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.092*5=0.46,0.46,TRUE
J4,PinHeader_1x03_P2.54mm_Vertical,1,Conn_01x03,https://www.lcsc.com/product-detail/C32713269.html?s_z=n_1x3%25202.54mm&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVVNWRFdXXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.0228*5=0.11,0.11,TRUE
"R1, R2",402,2,5.1K,https://www.lcsc.com/product-detail/C25905.html?s_z=n_0402WGF5101TCE&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVl1fRlNbUDsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.0008*100=0.08,0.08,TRUE
"R3, R4",402,2,27ohm,https://www.lcsc.com/product-detail/C25100.html?s_z=n_27ohm&spm=wm.ssy.bg.4.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVlxTR1ZeXjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.0008*100=0.08,0.08,TRUE
"R5, R6",402,2,1K,https://www.lcsc.com/product-detail/C11702.html?s_z=n_0402WGF1001TCE&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVVRURFVaVjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.0007*100=0.07,0.07,TRUE
R7,402,1,10K,https://www.lcsc.com/product-detail/C60490.html?s_z=n_10k%25CE%25A9%2520&spm=wm.ssy.bg.1.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVVBWRFdaVzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.0008*100=0.08,0.08,TRUE
SW1,SW_Push_SPST_NO_Alps_SKRK,1,SW_Push,https://www.lcsc.com/product-detail/C720477.html?s_z=n_TS-1088-AR02016&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcV11eQlhYUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.055*10=0.55,0.55,TRUE
U1,QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm,1,RP2040,https://www.lcsc.com/product-detail/C2040.html?s_z=n_rp2040&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVlRURFBXXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.95,0.95,TRUE
U2,SOT-23,1,MCP1700x-330xxTT,https://www.lcsc.com/product-detail/C39051.html?s_z=n_MCP1700T-3302E%252FTT&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcVVRRT1JWUjsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.49*5=2.45,2.45,TRUE
U3,Winbond_USON-8-1EP_3x2mm_P0.5mm_EP0.2x1.6mm,1,W25Q16JVZPIQ TR,https://www.lcsc.com/product-detail/C2456208.html?s_z=n_W25Q16JVZPIQ%2520TR&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcV11SR1JaXzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,1.31,1.31,TRUE
Y1,Crystal_SMD_3225-4Pin_3.2x2.5mm,1,12 MHz,https://www.lcsc.com/product-detail/C9002.html?s_z=n_X322512MSB4SI&spm=wm.ssy.bg.0.xh&lcsc_vid=E1laAQVSFFhYUAYAEgcPUwUHRgNYVVBVEQUIAQIFRVgxVlNRQVBcV1xQT1NXVzsOAxUeFF5JWBYZEEoKFBINSQcJGk4dAgUUFAk%3D,0.073*10=0.73,0.73,TRUE
,JLCPCB,1,,https://cart.jlcpcb.com/quote/gerberviewThree/?qs=a23e7f3868a44292b2bc773764c7d804_1_0_4_0_0.html,2.1,2.1,TRUE
,T18-D24 Tip,1,,Hakko T18 Series 0.09 in. Chisel Tip - Micro Center,6.99,6.99,TRUE
,Wick,1,,iFixit Desoldering Wick - Micro Center,4.99,4.99,TRUE
,Rosin Flux,n/a,,CAIG Laboratories DeoxIT Brand No Clean RMA Soldering Flux in Syringe Applicator - Micro Center,7.99,0,TRUE
,Tweezers,1,,https://www.microcenter.com/product/361636/enkay-products-heat-resistant-soldering-tweezers-curved-point,2.99,2.99,TRUE
,Helping Hand and Magnifying Glass,1,,Inland Inland Adjustable Helping Hand w/ Magnifying Glass - Micro Center,4.99,4.99,TRUE
,,,,,,,
,,,,,Subtotal,,
,,,,,,30.87,
,,,,,Shipping and Handling,,
,,,,,LCSC,12.12,
,,,,,JLCPCB,3.12,
,,,,,,,
,,,,,Tax,,
,,,,,Micro Center,3.82,
,,,,,,,
,,,,,Total,,
,,,,,,49.93,
