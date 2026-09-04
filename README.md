# graylog

Graylog Pipeline

The pipeline_content_pack.json file contains the pipeline configurations and rules for the following input types:

 - DHCPD
 - Maltrail
 - NAXSI
 - Netflow
 - OPNsense
 - Pihole/Unbound DNS/DNSMasq
 - Suricata
 - Zenarmor


## License

Dual-licensed, **attribution required** under both:

- **Code & configuration** (scripts, rules, decoders, pipelines, configs): [Apache License 2.0](LICENSE)
- **Docs, guides & diagrams** (README, docs, diagrams): [CC BY 4.0](LICENSE-docs)

See [`LICENSING.md`](LICENSING.md) and [`NOTICE`](NOTICE). Credit: Lester E. Nichols III, secdoc.tech.

## GitLab CI baseline

GitLab CI validates tracked JSON, Python, and shell syntax, then runs a network-independent high-confidence secret scan across full Git history. The public pipeline contains no private registry, runner, credential, CA, or internal-domain reference.

