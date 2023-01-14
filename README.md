# CatRig

## What is this?

My build documentation for a [RatRig V-Core 3.1][ratrig].

## Part lists

Prices are in NZD, and assume no sale is currently on. All costs are per-part:
thus, the cost is multiplied by the number required. If something comes in
larger volumes than listed, the cost is per-part: for example, for screws that
come in packs of 10, the listed price will be one-tenth of the pack price.

Printed part costs assume use of [Prusament ASA][prusament-asa] with the RatRig
[recommended settings][ratrig-settings]. We will use two colours: a primary
colour (in my case, [Sapphire Blue][prusament-asa-sapphire-blue]) and an accent
colour (in my case, [Galaxy Black][prusament-asa-galaxy-black]). Printed part
listings will indicate which colour you need for it.

## Sources

Everything here assumes someone building in New Zealand: in other areas, you
might have better options. Thus, Aliexpress sellers make a frequent appearance.
Some of these sellers are due to a good reputation in the community or good
personal experiences; we also use recommended suppliers for components if
they're on Aliexpress.

### Extruder

CatRig uses a [Sherpa Micro][sherpa-micro].

| Part name | Origin | Number required | Printed? | Cost per unit |
|---|---|---|---|---|
| Drive gears | [Trianglelab][drive-gears-tl] | 1 | No | 52.58 |
| NEMA14 8-tooth motor 17mm | [Mellow][nema-14-8t-mellow] | 1 | No | 38.94 |
| Front housing | [Annex Engineering][sherpa-front-housing-stl] | 1 | Accent | 0.05 |
| Idler arm | [Annex Engineering][sherpa-idler-arm-stl] | 1 | Accent | 0.11 |
| Housing core | [Annex Engineering][sherpa-housing-core-stl] | 1 | Primary | 0.27 |
| Housing rear | [Annex Engineering][sherpa-housing-rear-stl] | 1 | Primary | 0.10 |
| M3 x 20mm button socket head cap screw | [Liya][liya-m3-bsh] | 1 | No | 0.10 |
| M3 x 16mm button socket head cap screw | [Liya][liya-m3-bsh] | 2 | No | 0.09 |
| M3 x 8mm button socket head cap screw | [Liya][liya-m3-bsh] | 2 | No | 0.06 |
| 7mm OD x 5mm ID x 0.5mm steel washer | [Liya][liya-washer] | 1 | No | 0.05 |
| M3 x D5.0 x L4.0 brass insert | [HotXYZ][hotxyz-insert] | 4 | No | 0.13 |
| PTFE tube OD 4mm ID 2mm, 1m | [Mellow][ptfe-mellow] | 1 | No | 4.71 |

Total: **97.68**

### Hotend

CatRig uses a TD6S from Trianglelabs. Since it's almost a Rapido, we re-use the
Rapido EVA mount; that way, we get a rigid mount as well.

| Part name | Origin | Number required | Printed? | Cost per unit |
|---|---|---|---|---|
| TD6S Model A 24V without adapter | [Trianglelab][td6-model-a-tl] | 1 | No | 69.98 | 
| Undertaker V6 nozzle 0.4mm | [West3D][undertaker-west3d] | 1 | No | 74.00 |
| M2.5 x 8mm DIN 912 screw | [Liya][din912-liya] | 4 | No | 0.05 |
| M3 x D4.6 x L4.0 brass insert | [HotXYZ][hotxyz-insert] | 8 | No | 0.09 |
| 4010 dual-ball 24V DC fan | [Gdstime][4010-fan-gdstime] | 1 | No | 26.48 |
| M3 x 20mm DIN 912 screw | [Liya][din912-liya] | 4 | No | 0.10 |
| M3 x 6mm DIN 912 screw | [Liya][din912-liya] | 4 | No | 0.07 |
| PTFE tube OD 4mm ID 2mm, 30mm | [Mellow][ptfe-clear-mellow] | 1 | No | 0.10 |

[ratrig]: https://v-core.ratrig.com/
[drive-gears-tl]: https://www.aliexpress.com/item/1005003156582431.html
[nema-14-8t-mellow]: https://www.aliexpress.com/item/1005005124486943.html
[sherpa-micro]: https://github.com/Annex-Engineering/Sherpa_Micro-Extruder
[sherpa-front-housing-stl]: https://github.com/Annex-Engineering/Sherpa_Micro-Extruder/blob/main/STLs/%5Ba%5D_housing_front_x1_rev2.STL
[sherpa-idler-arm-stl]: https://github.com/Annex-Engineering/Sherpa_Micro-Extruder/blob/main/STLs/%5Ba%5D_idler_arm_long_x1_rev2.STL
[sherpa-housing-core-stl]: https://github.com/Annex-Engineering/Sherpa_Micro-Extruder/blob/main/STLs/housing_core_x1_rev2.STL
[sherpa-housing-rear-stl]: https://github.com/Annex-Engineering/Sherpa_Micro-Extruder/blob/main/STLs/housing_rear_x1_rev2.STL
[prusament-asa]: https://www.prusa3d.com/category/prusament-asa
[ratrig-settings]: https://v-core.ratrig.com/printed_parts/#recommended-print-settings
[liya-m3-bsh]: https://www.aliexpress.com/item/32810852732.html
[liya-washer]: https://www.aliexpress.com/item/4000316011573.html
[hotxyz-insert]: https://www.aliexpress.com/item/4000232858343.html
[ptfe-mellow]: https://www.aliexpress.com/item/1005001370675514.html
[prusament-asa-sapphire-blue]: https://www.prusa3d.com/product/prusament-asa-sapphire-blue-850g
[prusament-asa-galaxy-black]: https://www.prusa3d.com/product/prusament-asa-prusa-galaxy-black-850g/
[td6-model-a-tl]: https://www.aliexpress.com/item/1005004704341801.html
[undertaker-west3d]: https://west3d.com/products/west3ds-undertaker-tungsten-carbide-nozzle?variant=42290761334996
[din912-liya]: https://www.aliexpress.com/item/32810872544.html
[4010-fan-gdstime]: https://www.aliexpress.com/item/32726644469.html
[ptfe-clear-mellow]: https://www.aliexpress.com/item/32970391631.html
