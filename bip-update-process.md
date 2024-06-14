<pre>
  BIP: ?
  Title: Updated BIP Process
  Author: Murch <murch@murch.one>
  Comments-URI: https://github.com/bitcoin/bips/wiki/Comments:BIP-Updated-BIP-Process
  Status: Draft
  Type: Process
  Created: 2024-05-13
  License: CC0-1.0
  Replaces: 2
</pre>

## Abstract

A _Bitcoin improvement proposal (BIP)_ provides a concise, self-contained, technical description of one new concept,
feature, standard, implementation guideline, best-practice, design, or incident report relevant to the Bitcoin community.

The BIPs repository serves as a highly visible platform to put forward mature proposals. Because the BIPs are maintained
as text files in a versioned repository, their revision history is the historical record of each proposal.

This BIP replaces BIP 2 with a more well-defined and clear process, and may be amended to address future needs of the
BIP process.

## What is a BIP?

BIPs are intended to be the primary mechanism for proposing new protocol features, coordinating client standards, and
documenting design decisions that have gone into Bitcoin implementations. Each BIP is primarily owned by its authors,
the _BIP champions_, and represents the champions’ opinion or recommendation. The champions are expected to foster
discussion, address feedback and dissenting opinions, and, if applicable, advance adoption of their proposal within the
community.

### What is the significance of BIPs?
### What should be documented in a BIP?
### Types
#### Informational
#### Process
#### Standards Track

## Editors
### Responsibilities

## Format
### Specification
#### BIP Header Preamble
#### Auxiliary Files

## Workflow

The BIP process starts with an idea for Bitcoin. Each potential BIP must have one or multiple champions—the people
who write the BIP, shepherd the discussion in the appropriate forums, gather feedback from the community, and finally
recommend a mature proposal for adoption.

### Ideation

After having an idea, the champion should evaluate whether it is BIP-able. The idea must be of interest to the broader
community or relevant to multiple software projects. Small improvements and matters concerning only a single project
often do not require standardization and should instead be brought up to the relevant project directly. The champion
should research whether an idea has been discussed before. Many ideas in Bitcoin are being rediscovered time and again
that have been discussed and rejected for various reasons before. After some investigation, the novelty of an idea can
be tested by posting about it to the [Bitcoin development mailing list](https://groups.google.com/g/bitcoindev).

Vetting an idea publicly before investing the time to write a BIP is meant to save both the potential champion and the
wider community time. Asking the Bitcoin community first whether an idea is original helps prevent too much time being
spent on something that is guaranteed to be rejected based on prior discussions (searching the internet does not always
do the trick).
Describing it publicly also ensures that the idea is of interest to more people beside the champion. If the champion is
encouraged by interested responses, they may work on drafting a BIP for the idea. Once the draft has matured to a
presentable state, the champion should post the draft to the [Bitcoin development mailing
list](https://groups.google.com/g/bitcoindev) and open a pull request to the BIPs repository.

### Standards Track BIPs

#### Draft

Ideas that are on-topic, adhere to the formatting requirements, and have materially progressed beyond the ideation
phase, e.g. by generating substantial public discussion and commentary from diverse contributors, by being implemented
in multiple independent software projects, and the champion working for an extended period of time towards improving the
proposal based on the community feedback they gathered, the BIP will be assigned a number and the pull reuqest will be
merged to the reposity. While BIPs are author documents which must only meet certain minimum criteria, the BIP editors
strive to ensure there are not an unnecessary number of BIPs which never progress into broad implementation across the
bitcoin ecosystem. After the BIP is merged to the repository, its focus should not be shifted significantly, although
the specification may still be evolving.

#### Proposed

When the champion is confident that their BIP is ready for adoption by the Bitcoin community, they may update the BIP’s
status to _PROPOSED_ to indicate that they are seeking implementation of the BIP. The specification in the BIP should be
largely settled and should only be adjusted in minor details that may come up as projects implement the BIP.

#### Final

#### Withdrawn

### Process BIPs

### Informational BIPs

### Transferring Ownership

## Licensing

## Changes from BIP-2

## Copyright

This BIP is licensed under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.

## Related Work

- BIP-1
- BIP-2
