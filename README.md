# CompComHW2
Computer Communications, Assignment 2.

Analyzes a medium-traffic wireless local area network with packet sniffing in [Wireshark].

## Contents

#### Assignment

- [assn.pdf](https://github.com/Chatatata/CompComHW2/blob/master/assn.pdf): Assignment given in PDF format.

#### Report

- [report.md](https://github.com/Chatatata/CompComHW2/blob/master/report.md): First draft of the report written in [Markdown].

- [report.pages](https://github.com/Chatatata/CompComHW2/blob/master/report.pages): Page styling in [Pages].

- [report.pdf](https://github.com/Chatatata/CompComHW2/blob/master/report.pdf): Final report in PDF format. *You might better look for this.*

#### Wireshark PCAP files

##### Short-burst

- [short-burst-1-tcp-80-http-ip.pcap](https://github.com/Chatatata/CompComHW2/blob/master/short-burst-1-tcp-80-http-ip.pcap): Captured packets to be analyzed in [Wireshark] during short-burst.

##### Long-burst

- [long-burst.pcap](https://github.com/Chatatata/CompComHW2/blob/master/long-burst.pcap): Captured packets to be analyzed in [Wireshark] during long-burst.

#### CSV files

##### Short-burst

- [short-burst-1-tcp-80](https://github.com/Chatatata/CompComHW2/blob/master/short-burst-1-tcp-80): Packets with only `tcp:80` filter.

- [short-burst-1-tcp-80-http](https://github.com/Chatatata/CompComHW2/blob/master/short-burst-1-tcp-80-http): Packets with `tcp:80` and `http` filters.

- [short-burst-1-tcp-80-http-ip](https://github.com/Chatatata/CompComHW2/blob/master/short-burst-1-tcp-80-http-ip): Packets with `tcp:80`, `http` and IP address filters.

- [short-burst-1-tcp-80-nohttp](https://github.com/Chatatata/CompComHW2/blob/master/short-burst-1-tcp-80-nohttp): Packets with `tcp:80` and `not http` filters.

##### Long-burst

- [long-burst-1-retransmit](https://github.com/Chatatata/CompComHW2/blob/master/long-burst-1-retransmit): Retransmitted packets during long-burst.

## License

MIT

[Wireshark]: https://www.wireshark.org
[Markdown]: https://en.wikipedia.org/wiki/Markdown
[Pages]: https://www.apple.com/tr/pages/
