# Scope: what OPENLINK is and is not

## What OPENLINK is

OPENLINK is an interface specification for unmanned-system interoperability. It is published as Protocol Buffer message definitions under Apache-2.0 by Blekinge Institute of Technology in collaboration with Sjöstridsskolan, Swedish Naval Warfare Centre.

The published artefact is:

- `.proto` files defining registration, status, detection, tasking, and observation-provenance messages
- Conformance test vectors
- Reference scenarios
- Experiment reports
- This documentation

That is the entire deliverable.

## What OPENLINK is not

OPENLINK is not a product, a platform, a reference implementation, a runtime, a cryptographic library, or a deployed system.

OPENLINK does not provide and does not replace:

| Responsibility | Belongs to |
|---|---|
| Implementation of the interface | The adopter |
| Deployment and operational integration | The adopter |
| Export-control classification and licensing | The adopter, under applicable national law |
| Data protection and privacy compliance | The adopter, under applicable national and EU law |
| FDI screening and ownership-control review | The adopter, under applicable national law |
| Procurement-law compliance | The adopter, under applicable procurement regulation |
| Operational procedures and authorization | The adopter's command authority |
| Fitness for any particular operational purpose | Not warranted (see LICENSE) |

Adopting OPENLINK does not discharge any regulatory obligation. The interface defines message format and semantics. Everything above and below the interface is the adopter's domain.

## Publisher

Blekinge Institute of Technology (BTH), Karlskrona, Sweden, in collaboration with Sjöstridsskolan (Swedish Naval Warfare Centre, part of Försvarsmakten).

OPENLINK is published as academic research in interface specifications for sensor interoperability. The publisher does not assert that OPENLINK is, or is not, controlled under any national export-control regime. That determination is the responsibility of national authorities and of adopters in their own jurisdictions.

## Governance

Changes to the specification are proposed via pull request. Acceptance requires review by at least one maintainer from BTH and one from Sjöstridsskolan. Consensus is sought; where consensus cannot be reached, the BTH maintainer holds the deciding vote.

The specification follows semantic versioning. Breaking changes to message semantics require a major version increment and a migration guide.

## Relationship to other standards

OPENLINK is aligned with BSI Flex 335 (SAPIENT), which is on the NATO STANAG track for autonomous sensor and effector networks. OPENLINK is a complement, not a competitor. BSI Flex 335 covers the sensor-to-fusion interface. OPENLINK extends into observation provenance and maritime-domain tasking. Systems implementing BSI Flex 335 can expose an OPENLINK interface with an adapter; no replacement of existing SAPIENT integration is required.

Alignment with NATO Architecture Framework (NAF) and STANAG 4559 (coalition ISR interoperability) is a design goal, not a current compliance claim.

## Contributions

All contributions require DCO sign-off. By signing off, the contributor certifies that they have the right to submit the contribution under Apache-2.0 and that no export-controlled, classified, or proprietary material is included.

Contributors are responsible for ensuring their contributions comply with their own national export-control and employer IP obligations before submission.

## Contact

For questions about the specification: open a GitHub issue.

For questions about operational deployment or integration: those are outside the scope of this specification. Contact the organization implementing OPENLINK in your specific deployment.
