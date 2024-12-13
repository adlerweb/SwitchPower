# Switch Idle Power Stats

This list contains power consumtion values for several network switches
measured under idle load. Test are conducted with a single copper port
using 1000BASE-T (or 100BASE-TX for switches without a copper gigabit
port). Unless marked otherwise test was using factory defaults. All
values should only be used as rough estimate as most values are only
short time measurements, also grid voltage and network load can cause
variations.

| Vendor   | Model                    | Product Number    | RJ45 User Ports | Load  | Test Voltage | Notes             |
|----------|--------------------------|-------------------|-----------------|-------|--------------|-------------------|
| HP       | 2524                     | J4813A            | 24              |  23W  | 235V         | 100MBit/s only    |
| HP       | 2910al-24G PoE           | J9146A            | 24              |  43W  | 235V         |                   |
| Ubiquity | Unifi Switch 24 PoE 250W | US‑24‑250W        | 24              |  24W  | 235V         | Adopted           |
| Cisco    | Catalyst 2950            | WS-C2950-24       | 24              |  16W  | 235V         | 100MBit/s only    |
| Cisco    | Catalyst 2960-S 24TS-L   | C2960S-24TS-L     | 24              |  24W  | 234V         |                   |
| Cisco    | Catalyst 2960-S 48FPS-L  | C2960S-48FSP-L    | 48              |  54W  | 234V         |                   |
| Cisco    | Catalyst 3560X-48P-L     | C3560X-48P-L      | 48              | 100W  | 234V         | 1x715W PSU        |
| Ubiquity | Unifi Switch 48 PoE 500W | US‑48‑500W        | 48              |  39W  | 235V         | Adopted           |
| HP       | 2920al-24G PoE           | J9727A            | 24              |  38W  | 235V         | EEE no change     |
| HP       | 2920al-48G PoE           | J9729A            | 48              |  48W  | 222V         |                   |
| HP       | 2824                     | J4903A            | 24              |  45W  | 230V         |                   |
| HP       | 2610-24                  | J9085A            | 26              |  15W  | 230V         | 20x100 + 4x1000   |
| HP       | 2510G-24                 | J9279A            | 24              |  27W  | 230V         |                   |
| Dell     | POWERCONNECT 2724        | PowerConnect 2724 | 24              |  10W  |  12V         | Without stock PSU |
| SMC      | SMCGS24C                 | SMCGS24C          | 24              |  11W  |  12V         | Without stock PSU |
| HP       | 2930F-48G-PoE+           | JL256A            | 48              |  37W  | 235V         |                   |
| HP       | 2930M-48G-PoE+           | JL322A            | 48              |  42W  | 222V         | Single 1100W PSU  |
| HP       | 2530-24G-PoE+-2SFP+      | J9854A            | 24              |  28W  | 222V         |                   |
| HP       | 4104gl                   | J4887A+J4908A     | 24              |  75W  | 222V         |                   |
