# M470C · Input Pre Amps

Ward-Beck Systems M470C, 1977|10. Wiki page: [M470C on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M470C.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 12 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 4 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 9 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 130 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 5 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 21 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [5 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1977 - M470C - P002 - 1-1.jpg](MANUALS/1977%20-%20M470C%20-%20P002%20-%201-1.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivities** |  |
| &nbsp;&nbsp;Line | Mic Pad Mic: 10 +20 dBm (ref 600 ohm -40 10 dBm (ref 150 ohm 2: source -60 to -30 dBm (ref 150 ohm ±0.25 dB from 30 Hz to 20 kHz. 125 dBm EIN at maximum sensitivity (20 Hz to 20 kHz) 75 dB S/N ratio or better for Tine sensitivities from to +20 dBm |
| **Noise** |  |
| &nbsp;&nbsp;Harmonic distortion | Less than 0.358 from 30 Hz to 15 kHz at +24 dBm output or Ies s Less than 0.1&quot; at 1 kHz at +24 dBm output. |
| **Source impedances** | Line Mic 150/600 ohms ba Tanced/unba lanced 150 ohms bajanced/unbalanced |
| **Input impedances** | Line Mic 30,000 ohms 750 ohms minimum. |
| **Output impedance** | Less than 100 ohms at insert and direct outputs |
| **Load impedance** | 600 ohms balanced (at insertion point) 10k ohms balanced (at direct output) |
| **Output level** | dBm nomina 1, +26 dBm maximum. |
| **Phasing** | Input and output termina is designated by numbers are in Phase |
| **Power requirements** | +25 volts dc, 20 ma nomina], 80 MA maximum |
| **Ambient temperature** | to 60 degrees Celsius wide 14.15&quot; high hm} 6.5 &quot; deep {4i mm X 360 mm 165 |

## Circuit description

From [1977 - M470C - Input Module (2).pdf](MANUALS/1977%20-%20M470C%20-%20Input%20Module%20(2).pdf) pages 5-9 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**H470C INPUT MODULE**

DIRECT Output The output signal of the booster amplifier feeds the DIRECT output a t connector Pl, pins 3/C. This output is designed to operate into abridging load of 10 1: ohms or higher. The nominal level of the DJRECT output is 0 dBm.

HASTER, SUBHASTER and AUXILIARY Outputs The booster amp l t rte r also provides the feeds for the left and right HASTER and SUBHASTER outputs via PANs....i tch SII13 and PAN control RB4 through R8J. Additional feeds are supplied to the SOLO output via SWll and to the four AUXILIARY outputs....hen in the POSTFADE mode. With the exception of the DIRECT output, all outputs are designed a s 30 1: ohm current sources, to operate into zero impedance summing nodes. Each summing output is equipped....i th its own assignments....i tch.

Control Functions DC control and logic muting functions are provided through the HIC/L1NE INPUT Selector switchu and the CHANNEL ON switch to facilitate studio mute control functions. to minimize system transients, the dc current in these circuits should be limited to I mAo Further control contacts are provided on the SOLOs....i tch SWU as well as on all SUBHASTER and MASTER assignment switches.

Power Supply Dec o up l i nq Power sup ply dec oupling is provided by OlD, 011 and their assoc ia ted components. The decoup ling ne twc r k reduces the module voltage tot lO volts from the nominal sup ply voltage of:!:l5 volts..

**FREQUENCY IN HERTZ**

WAR D-B E CK SYSTEMS L T C.

**K470 C INPUT MODULE**

PART DESCRIPTION.FG KFG PART NUMBER C1 C'Pl~ Ito r 0.047 uF ase t cc C092 -MC-47311 02 I u F/3 S V Kellet T39 DBI 0 5H035 A$ 03 330 pF Ph! 1i ps 2222 -630 -03331 C4 220 pF 2222 -630 -0322 1 OS 330 pF 2222 -6 30 -0333 1 CO 47 pF 2 2 2 2-6 38 -704 19 C7 22 uF!2SY K e~ et T39D022~M02SAS

cs 2.7 pF Philips 2222-638 -032 78 C1.15 0 uF/6 Y Kelle t T39 DEI5 7110 0 6A$ Cl1 3.9 p F Philips 2222 -638 -09398 C12 33 uF IlO Y ee.. e t 13 900336110 10AS C13 0.22 uF /lOO V Ph!l1p s 344CHA220K C1' 0.1 uFIlOO Y 344CHAI00K C15 4.7 u F/l O Y Kell et T390B475HOI0A$ C1.6ele;e C17 22 pF UU -638 -58229 C18 150 p F 2222-638-7 015 1 m 4.7 pF UU -638 -094 78 02.22 p F 2222-638-5822 9 C2I 220 u~ /lO Y xeee t T3 9 0F 2 2? MOI OA5

C23 0.022 uF as e tcc C092 - KC-223&quot; 02 ' delete C25 0.0 22 u F Aseleo (092KC-223&quot; C26 1 ur/35 V Kelle t T3908105&quot; 03 5A$ C27 220 pF Philips 2222 -630 -03221 C28 33 uF !10 V Ke~et T390033~MOIOA$

C30 4.7 pF Philips 2222 -63 8-09 478

03 1

C32 68 uF!6 V K e~ e t T 390D68~HOO6A5

C34 s t ~ me ns 8 4 13 1 3A5226 - Z

22 uF!2S V

f!lli....!:.ill

**M47 0C INPUT MOOULE**

PART OESCRIPTION &quot; FG MFG PART NUMBER C36 C.p.~1 tor 22 uF! 2 5 V s r eee ns B 41313 -~5226 -Z

CR! Oiod: Motorola 1N400 3

F.l rc llll d HO!orol.

l N~ I 4B

**CRIO**

CRll

**CRI 5**

LED, yellow fa!rclll1d Fl Vl17 FlV4JO DSJ light bulb Sch.dow L22, 28 V

QI Tran !1sto r N.!1on.l 2N4'0 1

**PN3569**

OS PN364S

&quot;OS 2N2102

Q7 2N4037

2N2l02

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV09VS3FBdFphN3c/view?resourcekey=0-Y_UZKq6Z4NoJYbX0yk3zXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV09VS3FBdFphN3c&resourcekey=0-Y_UZKq6Z4NoJYbX0yk3zXw" width="240" alt="1977 - M470C - 470-04-010 - ADDI ONA EQUIPPED WITH CONTACTS.jpg"></a><br><sub>1977|10 · 470-04-010 - ADDI ONA EQUIPPED WITH CONTACTS · <a href="MECHANICAL/1977%20-%20M470C%20-%20470-04-010%20-%20ADDI%20ONA%20EQUIPPED%20WITH%20CONTACTS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcy05RjR3ZUhMVDg/view?resourcekey=0-MpJh5QYxqx17oMuXbMJfuw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcy05RjR3ZUhMVDg&resourcekey=0-MpJh5QYxqx17oMuXbMJfuw" width="240" alt="1977 - M470C - 470-01-004 - INPUT MODULE.jpg"></a><br><sub>1977|10 · 470-01-004 - INPUT MODULE · <a href="SCHEMATICS/1977%20-%20M470C%20-%20470-01-004%20-%20INPUT%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdDgyeW9rUUR5UUU/view?resourcekey=0-vHnow9OqBVq-cYQzzLn1Bw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdDgyeW9rUUR5UUU&resourcekey=0-vHnow9OqBVq-cYQzzLn1Bw" width="240" alt="1977 - M470C - 470-02-004 - INPUT MODULE SSCAL SCHEMATIC.jpg"></a><br><sub>1977|10 · 470-02-004 - INPUT MODULE SSCAL SCHEMATIC · <a href="SCHEMATICS/1977%20-%20M470C%20-%20470-02-004%20-%20INPUT%20MODULE%20SSCAL%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVNSMW5wX2VjNjA/view?resourcekey=0-oe2ITLc6ciKOmTrPQksYEw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVNSMW5wX2VjNjA&resourcekey=0-oe2ITLc6ciKOmTrPQksYEw" width="240" alt="1977 - M470C - 470-06-004 - SIDE ISSMOD ICKD USED.jpg"></a><br><sub>1977|10 · 470-06-004 - SIDE ISSMOD ICKD USED · <a href="SCHEMATICS/1977%20-%20M470C%20-%20470-06-004%20-%20SIDE%20ISSMOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdnlXMjJ0QTVtZm8/view?resourcekey=0-C5eTHfWY-8PfIcMIsZNxPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdnlXMjJ0QTVtZm8&resourcekey=0-C5eTHfWY-8PfIcMIsZNxPQ" width="240" alt="1977 - M470C - 470-04-008 - CONNECTOR REAR VIEW.jpg"></a><br><sub>1977|10 · 470-04-008 - CONNECTOR REAR VIEW · <a href="PINOUTS/1977%20-%20M470C%20-%20470-04-008%20-%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M470C - RTO-144 Connections.pdf`

## RTO-144 pinout

3 contacts, 22 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | M2 OUT | out | A3 + | high |
| 1 | LINE IN | in | A1 + | high |
| 2 | SUB OUT | out |  | medium |
| 2 |  | unread |  | low |
| 3 | OUTPUT SIGNAL OF THE BOOSTER AMPLIFIER | out |  | medium |
| 3 | SUB OUT | out |  | medium |
| 3 | DIRECT OUT | out | A4 + | high |
| 4 | SUB | other |  | medium |
| 4 | SHIELD | ground |  | medium |
| 5 | MASTER OUT | out |  | medium |
| 5 | FADER RETURN | in | B4 + | high |
| 6 | SUB OUT | out |  | medium |
| 6 | INSERT RETURN | in | B2 + | high |
| 7 | SUB OUT | out |  | medium |
| 7 | CH ON SWITCH OUT | control | B3 + | high |
| 8 | SUB OUT | out |  | medium |
| 8 | INSERT OUT | out | B1 + | high |
| 9 | AUX | other |  | medium |
| 9 | NC | nc |  | medium |
| 10 | AUX | other |  | medium |
| 10 | MASTER CTL | control |  | medium |
| 11 | AUX OUT | out |  | medium |
| 11 | SUB 6 CTL | control |  | medium |
| 12 | AUX OUT | out |  | medium |
| 12 | SUB CTL | control |  | medium |
| 13 | PFL | audio |  | medium |
| 13 | SUB CTL | control |  | medium |
| 14 | SOLO | audio |  | medium |
| 14 | MASTER CTL | control |  | medium |
| 15 | NC | nc |  | medium |
| 16 | NC | nc |  | medium |
| 16 | CTL | control |  | medium |
| 17 | NC | nc |  | medium |
| 17 | MIC 2 MUTE CTL | control |  | medium |
| 18 | NC | nc |  | medium |
| 18 | COMMON | ground |  | high |
| 19 | MIC IN 1 | in | A2 + | high |
| 19 | -25 V | power |  | high |
| 20 | MIC | in |  | medium |
| 20 | COMMON | ground |  | high |
| 21 | MIC SHIELD | ground |  | medium |
| 21 | +25 V | power |  | high |
| 22 | EQUAL N | other |  | medium |
| 22 | CHASSIS | ground |  | high |
| A | M2 OUT | out | A3 - | high |
| A | LINE IN | in | A1 - | high |
| B | SUB OUT | out |  | medium |
| C | SUB OUT | out |  | medium |
| C | DIRECT OUT | out | A4 - | high |
| D | SUB OUT | out |  | medium |
| E | MASTER OUT | out |  | medium |
| E | FADER RETURN | in | B4 - | high |
| F | SUB OUT | out |  | medium |
| F | INSERT RETURN | in | B2 - | high |
| H | SUB OUT | out |  | medium |
| H | CH ON SWITCH OUT | control | B3 - | high |
| J | SUB OUT | out |  | medium |
| J | INSERT OUT | out | B1 - | high |
| K | AUX 4 OUT | out |  | medium |
| K | NC | nc |  | medium |
| L | AUX OUT | out |  | medium |
| L | MASTER CTL | control |  | medium |
| M | AUX 2 OUT | out |  | medium |
| M | SUB 5 CTL | control |  | medium |
| N | AUX | other |  | medium |
| N | SUB 3 CTL | control |  | medium |
| P | PFL | audio |  | medium |
| P | SUB CTL | control |  | medium |
| R | SOLO | audio |  | medium |
| R | SUB CTL COM | ground |  | medium |
| S | NC | nc |  | medium |
| S | CH ON AUX | control |  | medium |
| T | NC | nc |  | medium |
| T | LINE MUTE CTL | control |  | medium |
| U | NC | nc |  | medium |
| U | MUTE CTL | control |  | medium |
| V | NC | nc |  | medium |
| V | SOLO CTL | control |  | medium |
| W | MIC IN 1 | in | A2 - | high |
| W | CH ON CTL COM | ground |  | medium |
| X | MIC | in |  | medium |
| X | MIC/LINE CTL COM | ground |  | medium |
| Y | MIC SHIELD | ground |  | medium |
| Y | +24 V | power |  | high |
| Z | EQUAL OUT | out |  | medium |
| Z | CH ON LAMP | control |  | medium |

**Straps:** CH ON LAMP: JMP.Z.W · CH ON GND : JMP.2 · 24V Jumper: JMP.Y.21 · CH ON GND : JMP.20.18 · Insert +: JMP.8.6 · Insert -: JMP.J.F · Fader +: JMP.7.5 · Fader - : JMP.H.E · EQ BYPASS: JMP.Z.22

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMzBvaU5pcW1Ka00/view?resourcekey=0-PDkTiK34MDMc6C7e4W2EoQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMzBvaU5pcW1Ka00&resourcekey=0-PDkTiK34MDMc6C7e4W2EoQ" width="240" alt="1977 - M470C - Input Module (2).pdf"></a><br><sub>1977|10 · Input Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUTQ2R2dCU2JjT1U/view?resourcekey=0-nhp-cEdZ50aNNOLC49UKWA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUTQ2R2dCU2JjT1U&resourcekey=0-nhp-cEdZ50aNNOLC49UKWA" width="240" alt="1977 - M470C - Input Module.pdf"></a><br><sub>1977|10 · Input Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdVlZNVR3VDVvSEU/view?resourcekey=0-ORBJnX4owQoFdGjOWQ23Zw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdVlZNVR3VDVvSEU&resourcekey=0-ORBJnX4owQoFdGjOWQ23Zw" width="240" alt="1977 - M470C - P001 - Title Page.jpg"></a><br><sub>1977|10 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdi1WV1JPSTFVVHM/view?resourcekey=0--L3iBg5p94YCyCoe9h-krw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdi1WV1JPSTFVVHM&resourcekey=0--L3iBg5p94YCyCoe9h-krw" width="240" alt="1977 - M470C - P002 - 1-1.jpg"></a><br><sub>1977|10 · P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQTFDVG9rSm9CMGs/view?resourcekey=0-3F2chpfC2EAH_3zJoM6uMg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQTFDVG9rSm9CMGs&resourcekey=0-3F2chpfC2EAH_3zJoM6uMg" width="240" alt="1977 - M470C - P003 - 2-1.jpg"></a><br><sub>1977|10 · P003 - 2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNzI1UVU3ZHBPUms/view?resourcekey=0-wqJo-sxSYtfap1CndJNn4Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNzI1UVU3ZHBPUms&resourcekey=0-wqJo-sxSYtfap1CndJNn4Q" width="240" alt="1977 - M470C - P004 - 2-2.jpg"></a><br><sub>1977|10 · P004 - 2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdVV1OTZKVGVJMGs/view?resourcekey=0-eAgquYWnbwn39_7TGE6WRg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdVV1OTZKVGVJMGs&resourcekey=0-eAgquYWnbwn39_7TGE6WRg" width="240" alt="1977 - M470C - P005 - 2-3.jpg"></a><br><sub>1977|10 · P005 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa1RMLWZfdkNfME0/view?resourcekey=0-YS9FkQDUu5L0ks766pIoGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa1RMLWZfdkNfME0&resourcekey=0-YS9FkQDUu5L0ks766pIoGw" width="240" alt="1977 - M470C - P006 - 3-1.jpg"></a><br><sub>1977|10 · P006 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLWx1dEdjWVY2VXc/view?resourcekey=0-Ie54OkXWHJ9CMdI8CcMxkg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLWx1dEdjWVY2VXc&resourcekey=0-Ie54OkXWHJ9CMdI8CcMxkg" width="240" alt="1977 - M470C - P007 - 4-1.jpg"></a><br><sub>1977|10 · P007 - 4-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUmVxLXFNdXF2dTA/view?resourcekey=0-QBvDvew5Q0fiZFtwGEhYPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUmVxLXFNdXF2dTA&resourcekey=0-QBvDvew5Q0fiZFtwGEhYPQ" width="240" alt="1977 - M470C - P008 - 4-2.jpg"></a><br><sub>1977|10 · P008 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX09RUmlIb050bEE/view?resourcekey=0-3gyMbNlPA52Kj5QWl6jCTA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX09RUmlIb050bEE&resourcekey=0-3gyMbNlPA52Kj5QWl6jCTA" width="240" alt="1977 - M470C - P009 - 4-3.jpg"></a><br><sub>1977|10 · P009 - 4-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSkJmQkFma2VWYXM/view?resourcekey=0-nFolpSScp8sz_Q_rGVmM5w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSkJmQkFma2VWYXM&resourcekey=0-nFolpSScp8sz_Q_rGVmM5w" width="240" alt="1977 - M470C - P010 - 4-4.jpg"></a><br><sub>1977|10 · P010 - 4-4</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeXhiYzhkNjRaMXc/view?resourcekey=0-bZpi4VgIjQkvBmQOYpB17A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeXhiYzhkNjRaMXc&resourcekey=0-bZpi4VgIjQkvBmQOYpB17A" width="240" alt="1977 - M470C - P011 - 4-5.jpg"></a><br><sub>1977|10 · P011 - 4-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQlpoRlB6UmxFS1U/view?resourcekey=0-XaeK4MBIJcGUsP78OOSJBA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQlpoRlB6UmxFS1U&resourcekey=0-XaeK4MBIJcGUsP78OOSJBA" width="240" alt="1977 - M470C - P012 - 4-6.jpg"></a><br><sub>1977|10 · P012 - 4-6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeDNkaEN2WUQ3V1k/view?resourcekey=0-kdVcZb0nitax1CkOm7U0lg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeDNkaEN2WUQ3V1k&resourcekey=0-kdVcZb0nitax1CkOm7U0lg" width="240" alt="1977 - M470C - P013 - 4-7.jpg"></a><br><sub>1977|10 · P013 - 4-7</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZWptdHpiNUw1aDQ/view?resourcekey=0-CBdF-Nv7xGI2xwNUQkfxhw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZWptdHpiNUw1aDQ&resourcekey=0-CBdF-Nv7xGI2xwNUQkfxhw" width="240" alt="1977 - M470C - P014 - 4-8.jpg"></a><br><sub>1977|10 · P014 - 4-8</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1977 - M470C - 470-01-004 - INPUT MODULE.kicad_sch](KICAD/1977%20-%20M470C%20-%20470-01-004%20-%20INPUT%20MODULE.kicad_sch)
- [1977 - M470C - 470-02-004 - INPUT MODULE SSCAL SCHEMATIC.kicad_sch](KICAD/1977%20-%20M470C%20-%20470-02-004%20-%20INPUT%20MODULE%20SSCAL%20SCHEMATIC.kicad_sch)
- [1977 - M470C - Input Module (2) p16.kicad_sch](KICAD/1977%20-%20M470C%20-%20Input%20Module%20(2)%20p16.kicad_sch)
- [1977 - M470C - Input Module p16.kicad_sch](KICAD/1977%20-%20M470C%20-%20Input%20Module%20p16.kicad_sch)
- [M470C.kicad_sym](KICAD/M470C.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
