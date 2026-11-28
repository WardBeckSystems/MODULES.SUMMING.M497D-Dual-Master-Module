# M497D Dual Master Module · Summing

Ward-Beck Systems M497D, 1978|11. Wiki page: [M497D on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M497D.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 41 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 6 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 195 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 12 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 31 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

## Specifications

From the technical data sheet: [1978 - M497D - P004 - 1-1.jpg](MANUALS/1978%20-%20M497D%20-%20P004%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | dB nominal +18 dB +/-0.5 dB maximum_ Master level control is provided |
| **Frequency response** | +/-0.2 dB from 20 Hz to 20 kHz. (tailored frequency response). |
| **Noise** | 75 dB below +8 dBm nominal output level (20 Hz to 20 kHz). |
| **Harmonic distortion** | Less than 0.05% THD from 30 Hz to 20 kHz at +27 dBm output or less: Less than 0.019 at kHz at +27 dBm output: |
| **Source impedances** | Summing: External: 30,000 ohms, balanced 600 ohms maximum; balanced |
| **Input impedances** | Summing: External: Less than ohms. 30,000 ohms: |
| **Input level** | External: dBm nominal, +16 dBm maximum |
| **Output impedances** | Program: Monitor; Mono: 60 ohms_ balanced. 60 ohms_ balanced, 36,000 ohms balanced. |
| **Load impedances** | Program: Monitor: Mono: 600 ohms balanced (minimum) Bridging, balanced (SK ohms minimum) Summing, less than ohms, balanced. |
| **Output level** | Program: Monitor; Mono: +8 dBm nominal, +28 dBm maximum (into onc 600 ohm load). +8 dBm nominal, +28 dBm maximum: +8 dBm nominal when summed into second M497D |
| **Channel separation** | dB between Left and Right channels (50 Hz to 15 kHz). |
| **Phasing** | Input and output terminals designated phase. numbers are |
| **Power requirements** | +/-25 volts dc, 50 mA nominal, 200 mA maximum |
| **Ambient temperature** | 60 degrees Celsius |
| **Dimensions** | 16&quot; wide x 7.0&quot; high 6.5&quot; dcep (41 mm 178 mm x 165 mm) |

## Circuit description

From [1978 - M497D - P005 - 2-1.jpg](MANUALS/1978%20-%20M497D%20-%20P005%20-%202-1.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M49TD accommodates two separate signal channels. It is designed to receive the mixed feeds from the left and right mixer buses of console_ The two signals arc independently processed and amplified to standard line levels The outputs of the M497D supply the main program outputs of the console system Both channels operate similar manner. The following description refers specifically to the LEFT channel. 66 ohm resistive dividing network; inserted between the 8-109E and the two module outputs at pins 12/N and 13/P_ Each of the two outputs has maximum drive capability +24 dBm into bridging load_ separate MONITOR output is providdesigned feed the M495 Stereo Monitor Module well to drive standard VU meter. Right_Chanael ad Mono_Output The signal originating from the external mixing network enters thc module pins and is applied to the summing current nodes of ZI and 22 The RIGHT channel of the M497D operates manner similar the left channel as described above. For the MONO output; both channels are combined and appear at pins [/M Thc signal level of this output 15 such that, when connected The summing input of second M497D it will produce output of dBm_ with the left right channel of the first unit operating at +8 dBm through Z3 with their associated components, provide an actively balanced input as well balanced output: Thc output operates at nominal level of 0 dBm and appears at pins 6/F_ Insert balanced INSERT point is provided between pins 6/F and 8 /J_ permitting the insertion of external equalizer filter compressor_ either using M499 Insert Switcher or by direct wiriPower_Supply_Decoupling An active power 'congcwia g o4PQy dccouplio8 network through provides isolation between the module and the +/-25 volt supply rails. Transistors Q3 and 06 monitor [he supply current: In the event of excessive power supply demands such as from component failure Or amplifier overdrive, the current flowing through Q and Q4 will bc limited Lerel_Adiustment From thc INSERT point_ the signal returned to the module at pins 8/J and fed the 8-109E output amplifier via attenuator network: R42 lcvcl trim potentiometer permitting adjustment the module output Icvel. small hole thc module front panel allows access to the trim control. Outline The 8-109E output amplifier operates wIth gain of 29 dB, It recovers thc loss of thc input network and provides additional gain product nominal line level of +8 dBm the output of the module Input

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKekJtb3BTRFMyRGM/view?resourcekey=0-YVxxQZIFz2VfqpQzG6E4Ww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKekJtb3BTRFMyRGM&resourcekey=0-YVxxQZIFz2VfqpQzG6E4Ww" width="240" alt="1978 - M497D - 497-04-007 - SPACE FOR CHANNEL IDENTIFICATION DESIGNATION.jpg"></a><br><sub>1978|11 · 497-04-007 - SPACE FOR CHANNEL IDENTIFICATION DESIGNATION · <a href="MECHANICAL/1978%20-%20M497D%20-%20497-04-007%20-%20SPACE%20FOR%20CHANNEL%20IDENTIFICATION%20DESIGNATION%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M497D.stl`](MECHANICAL/M497D.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M497D)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: 16" wide x 7.0" high 6.5" dcep (41 mm 178 mm x 165 mm))
- **From the drawing:** 4 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M497D - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M497D.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZHJuazRpOWlpS28/view?resourcekey=0-gSvIxljv3yjywfRO9tscEw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZHJuazRpOWlpS28&resourcekey=0-gSvIxljv3yjywfRO9tscEw" width="240" alt="1978 - M497D - 491-02-004 - DUAL MASTER MODULE.jpg"></a><br><sub>1978|11 · 491-02-004 - DUAL MASTER MODULE · <a href="SCHEMATICS/1978%20-%20M497D%20-%20491-02-004%20-%20DUAL%20MASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQjlHVUxwOE9pWUU/view?resourcekey=0-82bFS2K667TfM9GuJlG5iw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQjlHVUxwOE9pWUU&resourcekey=0-82bFS2K667TfM9GuJlG5iw" width="240" alt="1978 - M497D - 497-01-005 - DUAL MASTER MODULE FUNC TIONAL DIAGRAM.jpg"></a><br><sub>1978|11 · 497-01-005 - DUAL MASTER MODULE FUNC TIONAL DIAGRAM · <a href="SCHEMATICS/1978%20-%20M497D%20-%20497-01-005%20-%20DUAL%20MASTER%20MODULE%20FUNC%20TIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUVBaYWtOWWRJWXM/view?resourcekey=0-0ulyYKFkLQ5gbc22G7VaoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUVBaYWtOWWRJWXM&resourcekey=0-0ulyYKFkLQ5gbc22G7VaoQ" width="240" alt="1978 - M497D - 497-01-005 - OHMS LEFT LEVEL INSERT.jpg"></a><br><sub>1978|11 · 497-01-005 - OHMS LEFT LEVEL INSERT · <a href="SCHEMATICS/1978%20-%20M497D%20-%20497-01-005%20-%20OHMS%20LEFT%20LEVEL%20INSERT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ0lkU21zYWFkT0U/view?resourcekey=0-GRO3Jph-IDJxq0VSfTp42Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ0lkU21zYWFkT0U&resourcekey=0-GRO3Jph-IDJxq0VSfTp42Q" width="240" alt="1978 - M497D - 497-02-004 - TIPSOB CHASSIS.jpg"></a><br><sub>1978|11 · 497-02-004 - TIPSOB CHASSIS · <a href="SCHEMATICS/1978%20-%20M497D%20-%20497-02-004%20-%20TIPSOB%20CHASSIS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeUYtTmpCdUhwc00/view?resourcekey=0-yqnF0UbpTf3sjRknptYcvA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeUYtTmpCdUhwc00&resourcekey=0-yqnF0UbpTf3sjRknptYcvA" width="240" alt="1978 - M497D - 497-06-005 - DUAL MASTER MODULE.jpg"></a><br><sub>1978|11 · 497-06-005 - DUAL MASTER MODULE · <a href="SCHEMATICS/1978%20-%20M497D%20-%20497-06-005%20-%20DUAL%20MASTER%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUlNfZGZoRWtsNm8/view?resourcekey=0-ydOvPLwO6ouo715Ni5KyWQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUlNfZGZoRWtsNm8&resourcekey=0-ydOvPLwO6ouo715Ni5KyWQ" width="240" alt="1978 - M497D - 497-06-005 - TIPSOD WIPZST.jpg"></a><br><sub>1978|11 · 497-06-005 - TIPSOD WIPZST · <a href="SCHEMATICS/1978%20-%20M497D%20-%20497-06-005%20-%20TIPSOD%20WIPZST%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSTBsQU95SWdpNU0/view?resourcekey=0-ncXmewNHkAvzql0wLC9xiQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSTBsQU95SWdpNU0&resourcekey=0-ncXmewNHkAvzql0wLC9xiQ" width="240" alt="1978 - M497D - 8-109-02-006 - REVISION NOMINAL VALUE.jpg"></a><br><sub>1978|11 · 8-109-02-006 - REVISION NOMINAL VALUE · <a href="SCHEMATICS/1978%20-%20M497D%20-%208-109-02-006%20-%20REVISION%20NOMINAL%20VALUE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0JLM1gyVmVSd0k/view?resourcekey=0-6HuoOTC-IdFAaiqAHUj2_A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0JLM1gyVmVSd0k&resourcekey=0-6HuoOTC-IdFAaiqAHUj2_A" width="240" alt="1978 - M497D - 8-109-02-006 - RII RIZ.jpg"></a><br><sub>1978|11 · 8-109-02-006 - RII RIZ · <a href="SCHEMATICS/1978%20-%20M497D%20-%208-109-02-006%20-%20RII%20RIZ%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKanRZZ1Jnd28yUHc/view?resourcekey=0-dXb7yWrkgMDhNEQjBnNhbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKanRZZ1Jnd28yUHc&resourcekey=0-dXb7yWrkgMDhNEQjBnNhbw" width="240" alt="1978 - M497D - 8-109-06-006 - BOOSTER AMPLIFIER.jpg"></a><br><sub>1978|11 · 8-109-06-006 - BOOSTER AMPLIFIER · <a href="SCHEMATICS/1978%20-%20M497D%20-%208-109-06-006%20-%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM3dMLWNLV3FBTWc/view?resourcekey=0-HgTvzoHxRh3V1Ms1MN0ZdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM3dMLWNLV3FBTWc&resourcekey=0-HgTvzoHxRh3V1Ms1MN0ZdQ" width="240" alt="1978 - M497D - 8-109-06-006.jpg"></a><br><sub>1978|11 · 8-109-06-006 · <a href="SCHEMATICS/1978%20-%20M497D%20-%208-109-06-006%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M497D - RTO-144 Connections.pdf`

## RTO-144 pinout

21 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT SUM IN | in | A1 + | high |
| 2 | RIGHT SUM IN | in | A2 + | high |
| 4 | LEFT LINE IN | in | B1 + | high |
| 5 | RIGHT LINE IN | in | B2 + | high |
| 12 | OUT LEFT | out | A3 + | high |
| 14 | VU OUT LEFT | out | B3 + | high |
| 15 | OUT RIGHT | out | A4 + | high |
| 17 | VU OUT RIGHT | out | B4 + | high |
| 19 | -25 V | power |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| A | LEFT SUM IN | in | A1 - | high |
| B | RIGHT SUM IN | in | A2 - | high |
| D | LEFT LINE IN | in | B1 - | high |
| E | RIGHT LINE IN | in | B2 - | high |
| N | OUT LEFT | out | A3 - | high |
| R | VU OUT LEFT | out | B3 - | high |
| S | OUT RIGHT | out | A4 - | high |
| U | VU OUT RIGHT | out | B4 - | high |

**Straps:** Insert LEFT +: JMP.8.6 · Insert LEFT -: JMP.F.J · Insert Right +: JMP.7.9 · Insert Right -: JMP.H.K

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRTAyeU5mVENyeEk/view?resourcekey=0-AkCklO9DLolTZmDvr1VDeA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRTAyeU5mVENyeEk&resourcekey=0-AkCklO9DLolTZmDvr1VDeA" width="240" alt="1978 - M497D - Dual Master Module (2).pdf"></a><br><sub>1978|11 · Dual Master Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM18tY0hUWmtTRFU/view?resourcekey=0-RY5s6nYN3ahH9qAoKqE_Zg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM18tY0hUWmtTRFU&resourcekey=0-RY5s6nYN3ahH9qAoKqE_Zg" width="240" alt="1978 - M497D - Dual Master Module.pdf"></a><br><sub>1978|11 · Dual Master Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQWhZei1DQmlrTms/view?resourcekey=0-87KEs6RoJVJo5XZGsZZXRg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQWhZei1DQmlrTms&resourcekey=0-87KEs6RoJVJo5XZGsZZXRg" width="240" alt="1978 - M497D - P001 - Title Page.jpg"></a><br><sub>1978|11 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd29uaFVQbG01UDA/view?resourcekey=0-WTolpw4oZn1thbrDlopitw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd29uaFVQbG01UDA&resourcekey=0-WTolpw4oZn1thbrDlopitw" width="240" alt="1978 - M497D - P002.jpg"></a><br><sub>1978|11 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQndNS3lKXzh2a1k/view?resourcekey=0-8Dd-9YlOXGmBSas51NnWOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQndNS3lKXzh2a1k&resourcekey=0-8Dd-9YlOXGmBSas51NnWOQ" width="240" alt="1978 - M497D - P003.jpg"></a><br><sub>1978|11 · P003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeGFCNzJuQW1fdjQ/view?resourcekey=0-_KICyt8YbvIg3YhFY8Utdg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeGFCNzJuQW1fdjQ&resourcekey=0-_KICyt8YbvIg3YhFY8Utdg" width="240" alt="1978 - M497D - P004 - 1-1.jpg"></a><br><sub>1978|11 · P004 - 1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd1c2THRiUlpQNzA/view?resourcekey=0-i0R5sY8nKCeIUgdX4A-qqw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd1c2THRiUlpQNzA&resourcekey=0-i0R5sY8nKCeIUgdX4A-qqw" width="240" alt="1978 - M497D - P005 - 2-1.jpg"></a><br><sub>1978|11 · P005 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZHZ2eFdGOUVBZTQ/view?resourcekey=0-NW2-PIip2lUBSVF8gvU1-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZHZ2eFdGOUVBZTQ&resourcekey=0-NW2-PIip2lUBSVF8gvU1-g" width="240" alt="1978 - M497D - P006 - 3-1.jpg"></a><br><sub>1978|11 · P006 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHpQcWNpY0d3N3c/view?resourcekey=0-uwu1lf7s10rIsDL2wkuOBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHpQcWNpY0d3N3c&resourcekey=0-uwu1lf7s10rIsDL2wkuOBg" width="240" alt="1978 - M497D - P007 - 3-2.jpg"></a><br><sub>1978|11 · P007 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbHpGUS1DZTA2UWc/view?resourcekey=0-foPNwSlpdWS4sNQ0NF3V8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbHpGUS1DZTA2UWc&resourcekey=0-foPNwSlpdWS4sNQ0NF3V8Q" width="240" alt="1978 - M497D - P008 - 3-3.jpg"></a><br><sub>1978|11 · P008 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMUxXV2YxNHlQRms/view?resourcekey=0-DKrdGZutC7yI26Lrkz3m8Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMUxXV2YxNHlQRms&resourcekey=0-DKrdGZutC7yI26Lrkz3m8Q" width="240" alt="1978 - M497D - P009 - 4-1.jpg"></a><br><sub>1978|11 · P009 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaFAyYjRhSDVfY0k/view?resourcekey=0-gL10jdbyeT3edg2TkEpoPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaFAyYjRhSDVfY0k&resourcekey=0-gL10jdbyeT3edg2TkEpoPA" width="240" alt="1978 - M497D - P014.jpg"></a><br><sub>1978|11 · P014</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0t2VEJZSUhzVXM/view?resourcekey=0-7q_c0kZEjqIEU1plruiYlA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0t2VEJZSUhzVXM&resourcekey=0-7q_c0kZEjqIEU1plruiYlA" width="240" alt="1978 - M497D - P015 - 8-109.jpg"></a><br><sub>1978|11 · P015 - 8-109</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1VrOEoxcmM0Rm8/view?resourcekey=0-Lha0OH8tID5Aa0lydniIOw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1VrOEoxcmM0Rm8&resourcekey=0-Lha0OH8tID5Aa0lydniIOw" width="240" alt="1978 - M497D - P016 - 8-109-1-1.jpg"></a><br><sub>1978|11 · P016 - 8-109-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG5SNVpGek1JczQ/view?resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG5SNVpGek1JczQ&resourcekey=0-c3bGGRtUx4REu9z5KDRHmw" width="240" alt="1978 - M497D - P017 - 8-109-1-2.jpg"></a><br><sub>1978|11 · P017 - 8-109-1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXRGSER4Z2VZUjg/view?resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXRGSER4Z2VZUjg&resourcekey=0-mEgo4HzWAssWNPYvs9muVQ" width="240" alt="1978 - M497D - P018 - 8-109-2-1.jpg"></a><br><sub>1978|11 · P018 - 8-109-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOVhIS1l0dHZTOFk/view?resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOVhIS1l0dHZTOFk&resourcekey=0-iKCXHrvfdWx4Ke9-gFDYWg" width="240" alt="1978 - M497D - P019 - 8-109-2-2.jpg"></a><br><sub>1978|11 · P019 - 8-109-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEhSMFN4X1lnSjg/view?resourcekey=0-51aI3iimlChrQy4-0Vfs7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEhSMFN4X1lnSjg&resourcekey=0-51aI3iimlChrQy4-0Vfs7A" width="240" alt="1978 - M497D - P020 - 8-109-2-3.jpg"></a><br><sub>1978|11 · P020 - 8-109-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGNLVHZ2c2pzSnc/view?resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGNLVHZ2c2pzSnc&resourcekey=0-DkpuvXz-fODJn3c2X4IAkQ" width="240" alt="1978 - M497D - P021 - 8-109-2-4.jpg"></a><br><sub>1978|11 · P021 - 8-109-2-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ0pTTjJiTU5yOEk/view?resourcekey=0-I38P4wx8KdToHSF039nWHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ0pTTjJiTU5yOEk&resourcekey=0-I38P4wx8KdToHSF039nWHA" width="240" alt="1978 - M497D - P022 - 8-109-2-5.jpg"></a><br><sub>1978|11 · P022 - 8-109-2-5</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M497D - 491-02-004 - DUAL MASTER MODULE.kicad_sch](KICAD/1978%20-%20M497D%20-%20491-02-004%20-%20DUAL%20MASTER%20MODULE.kicad_sch)
- [1978 - M497D - 497-01-005 - DUAL MASTER MODULE FUNC TIONAL DIAGRAM.kicad_sch](KICAD/1978%20-%20M497D%20-%20497-01-005%20-%20DUAL%20MASTER%20MODULE%20FUNC%20TIONAL%20DIAGRAM.kicad_sch)
- [1978 - M497D - 497-01-005 - OHMS LEFT LEVEL INSERT.kicad_sch](KICAD/1978%20-%20M497D%20-%20497-01-005%20-%20OHMS%20LEFT%20LEVEL%20INSERT.kicad_sch)
- [1978 - M497D - 497-02-004 - TIPSOB CHASSIS.kicad_sch](KICAD/1978%20-%20M497D%20-%20497-02-004%20-%20TIPSOB%20CHASSIS.kicad_sch)
- [1978 - M497D - 8-109-02-006 - REVISION NOMINAL VALUE.kicad_sch](KICAD/1978%20-%20M497D%20-%208-109-02-006%20-%20REVISION%20NOMINAL%20VALUE.kicad_sch)
- [1978 - M497D - 8-109-02-006 - RII RIZ.kicad_sch](KICAD/1978%20-%20M497D%20-%208-109-02-006%20-%20RII%20RIZ.kicad_sch)
- [1978 - M497D - Dual Master Module (2) p13.kicad_sch](KICAD/1978%20-%20M497D%20-%20Dual%20Master%20Module%20(2)%20p13.kicad_sch)
- [1978 - M497D - Dual Master Module (2) p2.kicad_sch](KICAD/1978%20-%20M497D%20-%20Dual%20Master%20Module%20(2)%20p2.kicad_sch)
- [1978 - M497D - Dual Master Module p11.kicad_sch](KICAD/1978%20-%20M497D%20-%20Dual%20Master%20Module%20p11.kicad_sch)
- [1978 - M497D - Dual Master Module p27.kicad_sch](KICAD/1978%20-%20M497D%20-%20Dual%20Master%20Module%20p27.kicad_sch)
- [M497D.kicad_sym](KICAD/M497D.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
