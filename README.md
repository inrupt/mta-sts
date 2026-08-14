# MTA-STS for inrupt.com

This repository hosts the [MTA-STS](https://datatracker.ietf.org/doc/html/rfc8461) policy file for the `inrupt.com` domain, served via GitHub Pages at `mta-sts.inrupt.com`.

MTA-STS (Mail Transfer Agent Strict Transport Security) allows a domain to declare that it supports TLS for incoming email and that sending mail servers should refuse to deliver mail over unencrypted connections. This helps protect against downgrade attacks and passive eavesdropping on email in transit.

The policy file is served at `https://mta-sts.inrupt.com/.well-known/mta-sts.txt`.
