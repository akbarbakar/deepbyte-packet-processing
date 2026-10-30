# Result
- 960/960 rows, **0 lossy rows**, live accuracy == ACC_REF on **every** row.
- `tw` share of `te` >= 98.39 % in every row.
- NIC stress: 120/120 steps lossless; TRex reaches 9.947 Gbps at the 10 Gbps step, tcpreplay saturates at about 2.21 Gbps.
- The ISCXVPN2016 replay corpus (99,952 rows) is not the old draft's 10-pcap NonVPN set; per-class counts are in `result.csv`.
