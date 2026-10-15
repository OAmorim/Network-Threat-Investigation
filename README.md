# Network Threat Investigation with Wireshark

Three practical labs exploring what a packet capture can tell us: where suspicious downloads came from, which computer was involved, and what becomes visible when HTTPS traffic is decrypted.

The aim is simple: show the answer, explain how I found it, and support it with a Wireshark screenshot or a packet reference.

## Investigation workflow

Across the labs I used a repeatable network-investigation process:

1. Identify the affected host.
2. Review DNS and HTTP/TLS activity.
3. Follow relevant TCP streams.
4. Identify suspicious downloads and infrastructure.
5. Validate file types instead of relying on extensions.
6. Calculate and record file hashes.
7. Enrich external IP addresses with GeoIP context.
8. Separate evidence from assumptions.
9. Recommend additional endpoint investigation where network evidence alone is insufficient.

## Tools used

- Wireshark
- PowerShell (`Get-FileHash`)
- MaxMind GeoLite2
- VirusTotal (hash lookup only)

### The labs

- **[1. Investigating suspicious downloads](cases/01-malware-traffic/investigation.md)** — identify the files, website and Windows computer involved.
- **[2. Looking inside HTTPS](cases/02-tls-decryption/investigation.md)** — compare the same connection before and after adding the supplied TLS keys.
- **[3. Following a TrickBot infection](cases/03-trickbot/investigation.md)** — follow suspicious requests, disguised downloads and activity involving a domain controller.

### Skills shown

Display filters, DNS and HTTP inspection, TCP streams, Endpoints and Conversations, host identification, file hashes, TLS decryption and GeoIP.

These are training captures from different dates, not one continuous incident. The project contains reports and screenshots only. No malware, PCAPs, passwords or TLS secrets are included, and no suspicious files were executed.

[Sources and lab notes](docs/notes.md) · [Hash details](docs/hashes.md)
