Capacitor list for Nintendo Super NES, mainboard SNSP-CPU-01 and -02
=====================================================================

This is a PAL mainboard.

The sound chips are soldered straight to the mainboard.

SMD capacitor C59 is a 50V polarised type on SNSP-CPU-01,
and a 25V bipolar type on SNSP-CPU-02.

C59 *must* be changed to a bipolar type, since a polarised
capacitor at this position is an error in the schematic that
was revised in later revisions of the SNES.

THT capacitor C67 has three vias, allowing to choose either
a 5mm or a 7.5mm pitch capacitor.


Parts list
-----------

| Reference | Capacitance  | Voltage  | Type   | Diameter  | Pitch  | Height | Location | MLCC 0805 | MLCC 1206                      | Polymer  | New value | New voltage          |
|:----------|:-------------|:---------|:-------|:----------|:-------|:-------|:---------|:----------|:-------------------------------|:---------|:----------|:---------------------|
| C59       | 10 uF        | 25/50 V  | SMT    | 6.3 mm    |        |        |          |           | C13585                         |          |           | 50 V                 |
| C60       | 10 uF        | 50 V     | SMT    | 6.3 mm    |        |        |          |           | C13585                         |          |           | 50 V                 |
| C61       | 10 uF        | 50 V     | SMT    | 6.3 mm    |        |        |          |           | C13585                         |          |           | 50 V                 |
| C62       | 2.2 uF       | 50 V     | SMT    | 4.0 mm    |        |        |          | C377773   |                                |          |           | 50 V                 |
| C63       | 33 uF        | 25 V     | SMT    | 6.3 mm    |        |        |          |           | C12891                         |          | 22 uF     | 25 V                 |
| C64       | 33 uF        | 25 V     | SMT    | 6.3 mm    |        |        |          |           | C12891                         |          | 22 uF     | 25 V                 |
| C65       | 10 uF        | 50 V     | SMT    | 6.3 mm    |        |        |          |           | C13585                         |          |           | 50 V                 |
| C66       | 10 uF        | 50 V     | SMT    | 6.3 mm    |        |        |          |           | C13585                         |          |           | 50 V                 |
| C67       | 2200 uF      | 25 V     | Radial | 16 mm     | 7.5 mm |        |          |           |                                | C5438720 |           | 25 V                 |
| C73       | 47 uF        | 16 V     | SMT    | 6.3 mm    |        |        |          |           | C6105119<br>C385907<br>C403725 |          |           | 16 V<br>16 V<br>25 V |
