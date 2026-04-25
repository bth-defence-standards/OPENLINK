# OPENLINK

**The open data link for unmanned systems.**

An interface specification for sensor interoperability, published as publicly available academic research. Apache-2.0.

Aligned with [BSI Flex 335](https://knowledge.bsigroup.com/products/sapient-network-of-autonomous-sensors-and-effectors-interface-control-document-specification/standard) (SAPIENT, on the NATO STANAG track).

Published by Blekinge Institute of Technology with Sjöstridsskolan (Swedish Naval Warfare Centre), Karlskrona.

## Why

Every sensor speaks a different dialect. Integration today means bilateral agreements and vendor lock-in. OPENLINK is the open interface that ends that. One published message format. Any vendor can implement it. Any nation can adopt it.

## What it is

Protocol Buffer definitions for registration, status, detection, tasking, and observation-provenance messages, with maritime-domain extensions.

Every observation that passes through OPENLINK carries provenance: who observed, when, at what confidence, in a machine-readable format defined by the standard and, when signed, cryptographically verifiable.

Proto files and documentation. No reference implementation, no runtime, no owner, no gatekeeper.

## Adopt

Add one line to experiment or procurement requirements:

> *Sensors and visualizers shall expose an OPENLINK interface.*

## Evidence

Experiment reports are published in [`experiments/`](experiments/) after each operational use.

## License and scope

Apache-2.0. See [LICENSE](LICENSE). Contributions require [DCO sign-off](https://developercertificate.org/) (`git commit -s`).

OPENLINK defines the interface. Implementation, deployment, and operational compliance are the adopter's responsibility. See [SCOPE.md](SCOPE.md).
