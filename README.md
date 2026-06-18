# PWS as a Mass Surveillance Primitive

## Exploiting 5G Public Warning Systems for Zero-Knowledge Presence Detection

**Seminar:** Privacy and Security in Critical Infrastructure  
**Presenters:** Nandana Harikumar  ,  Dias Amitullayev

**Research Focus:** 5G NR Public Warning System (PWS) · 3GPP TS 38.331 Protocol Analysis

---

## Overview

This research demonstrates that a spoofed ETWS (Earthquake and Tsunami Warning System) paging message, combined with on-demand SIB delivery configuration, forces all idle 5G devices to transmit PRACH preambles simultaneously. This involuntary uplink burst can be passively detected by an eavesdropper with commodity hardware (~$300 SDR), enabling zero-knowledge mass presence detection without recovering any device identity.


## Research Questions

**RQ1: Protocol Validation** — Does 3GPP-mandated behavior force involuntary PRACH transmission when PWS uses on-demand SIB delivery?

**RQ2: Physical Detectability** — Can a passive eavesdropper with commodity hardware detect the resulting PRACH burst at urban distances?

---



## References

[1] J. Lee, G. Lee, J. Lee, Y. Im, M. Hollingsworth, E. Wustrow, D. Grunwald, and S. Ha. "Securing the wireless emergency alerts system." Communications of the ACM, 64(10), 85–93, 2021. https://doi.org/10.1145/3481042

[2] S. Tomasin, M. Centenaro, G. Seco-Granados, S. Roth, A. Sezgin. "Location-Privacy Leakage and Integrated Solutions for 5G Cellular Networks and Beyond." Sensors, 21(15):5176, 2021. doi: 10.3390/s21155176

[3] S. R. Hussain, M. Echeverria, O. Chowdhury, N. Li, E. Bertino. "Privacy Attacks to the 4G and 5G Cellular Paging Protocols Using Side Channel Information." NDSS 2019. https://doi.org/10.14722/ndss.2019.23442

[4] E. Bitsikas and C. Pöpper. "You have been warned: Abusing 5G's Warning and Emergency Systems." ACSAC 2022. https://doi.org/10.1145/3564625.3568000

[5] 3GPP TS 38.331 V17.13.0 — "NR; Radio Resource Control (RRC) protocol specification"

[6] 3GPP TS 38.321 — "NR; Medium Access Control (MAC) protocol specification"

[7] 3GPP TR 38.901 V16.1.0 — "Study on channel model for frequencies from 0.5 to 100 GHz"

[8] 3GPP TS 38.211 — "NR; Physical channels and modulation"

[9] 3GPP TS 38.101-1 — "NR; UE radio transmission and reception; Part 1: Range 1"

[10] Sunway QoE-Aware Dataset — https://data.mendeley.com/datasets/dx5xyyfz2y/1

---

## Disclosure

AI (Claude, Anthropic) was used to assist with:
- Understanding UERANSIM's internal API and source code structure
- Writing the source code modifications
- Developing the Monte Carlo simulation methodology
- Analyzing the Sunway dataset

The attack concept, protocol analysis, 3GPP specification interpretation and research conclusions are the authors' own work.

---

## License

This research is for academic purposes only. The attack described is a vulnerability disclosure intended to improve 5G security. Do not use this information to conduct unauthorized surveillance or disrupt emergency alert systems.
