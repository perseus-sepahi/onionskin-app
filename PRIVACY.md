# Onionskin privacy policy

*Last updated: 17 October 2026*

Onionskin collects no personal data. It has no accounts, no analytics, no crash reporting and no
advertising, and it never sends anything to its developer.

## What stays on your Mac

- The list of apps you protect and your settings, in
  `~/Library/Application Support/Onionskin/`.
- Tor's working files (directory cache and guard choices) in the same folder.
- The activity list (which hosts protected apps connected to). It is kept in memory only, is
  never written to disk, and is cleared when Onionskin quits.

## Network connections Onionskin makes

- **The Tor network.** Onionskin runs Tor, which connects to Tor relays (or to the bridges you
  choose) to build circuits. Traffic from the apps you protect travels through those circuits.
- **check.torproject.org**, through Tor, to show which exit address websites see. The Tor
  Project operates this service.

Apps you don't protect are not inspected beyond deciding that they are not protected. Their
connections pass through unchanged and are not logged.

## Contact

Questions: open an issue at <https://github.com/perseus-sepahi/onionskin-app/issues>.
