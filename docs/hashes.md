# File hashes and original captures

These values support the answers in the labs. A hash identifies bytes; it does not show that a file ran.

## Lab 1 downloads

**Flash — 8,227 bytes, response 2394**

- MD5: `7b3baa7d6bb3720f369219789e38d6ab`
- SHA-256: `e2e33b802a0d939d07bd8291f23484c2f68ccc33dc0655eb4493e5d3aebc0747`

**Java archive — 10,606 bytes, response 2489**

- MD5: `1e34fdebbf655cebea78b45e43520ddf`
- SHA-256: `178be0ed83a7a9020121dee1c305fd6ca3b74d15836835cfb1684da0b44190d3`

**Opaque download — 401,811 bytes, responses 1991, 2379 and 2977**

- MD5: `d276c86dcdbcdb6b74ee02496bc90d98`
- SHA-256: `ce5d1c41f6ca739f6c69f175a8f688334df2ea4d2e0fb5e3243ae01efd251e81`

The last hash belongs to the recovered HTTP bytes, not a decoded Windows executable. A fourth matching request received an empty response, so I counted three full transfers.

## Lab 3 downloads

The two PE hashes are included beside the download explanation in [lab 3](../cases/03-trickbot/investigation.md).

## Original capture fingerprints

Original files remain in the private lab. Their SHA-256 values are:

- 2014-11-16-traffic-analysis-exercise.pcap: `0e3fac547536f773bf1a21180a2294a10be97e956f091d24e168f147ecf5fafd`
- How to Decrypt Traffic with Wireshark.pcapng: `7a116baddd5b3680e8e019b1304ce5a1d775044cc908b79fef15d6a3a034a723`
- 2020-05-28-traffic-analysis-exercise.pcap: `34f77c61a58be8816fb42639a8b76178462cf6350899097cd8e7ac825f972797`
