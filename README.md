# Cross-Ethereum Specification Repository

This repository is for draft and implemented non-consensus-layer
specifications for Ethereum-like blockchains and related projects.

We welcome and encourage Ethereum-compatible blockchain developers to
contribute specifications for wider community to review. However, we
don't accept consensus-layer specifications. Use EIPs or ECIPs for
them.

## Goals

* **Shared innovation**: it wastes review efforts to duplicate
  specifications between EIPs and ECIPs for non-consensus-layer
  changes. Sharing innovations across teams and blockchains can be
  more effective.
* **Focus on standardization**: Unlike BIP, EIP or ECIP process,
  non-consensus-layer sepcifications are less political. Arguments
  won't be on whether a certain technology **should** happen, but
  **how** it would happen.
  
## Process

We currently use an informal IETF-like process, following [RFC
2026](https://www.ietf.org/rfc/rfc2026.txt). Every specification has
its maturity level:

* A new specification is sent in a pull request. The editor checks and
  helps the author to move the specification into an acceptable
  quality. After that, the specification is merged in **Proposed**
  maturity level. In this process, the specification gets its RFC
  number in the format of `spec-$year-$number-$feature`.
* When at least one implementation is done for a particular
  specification, it is moved to **Draft** maturity level.
* When significant implementations and successful operational
  experiences have been obtained, the specification is moved to
  **Standard** maturity level. Besides its RFC number, specifications
  in this maturity level also get a STD number in the format of
  `ethoxy-$number-$feature`. Specifications may continue to evolve or be replaced
  by newer specifications.

The current editor is `Wei Tang <hi@that.world>`.

Technically this process also support non-standards track, but
currently we assume all submitted specifications are on the standards
track.

## Specifications

| Number                                                   | Title                              | Author   | Maturity Level | Discussion                                     |
|----------------------------------------------------------|------------------------------------|----------|----------------|------------------------------------------------|
| [spec-2017-0001](specs/spec-2017-0001-evm-jets.md)       | Jets in Ethereum Virtual Machine   | Wei Tang | Proposed       | [#1](https://github.com/ethoxy/specs/issues/1) |
| [spec-2017-0002](specs/spec-2017-0002-rlp-media-type.md) | Recursive Length Prefix Media Type | Wei Tang | Proposed       | [#2](https://github.com/ethoxy/specs/issues/2) |
| [spec-2017-0003](specs/spec-2017-0003-evmjson.md)        | Ethereum Virtual Machine JSON-RPC  | Wei Tang | Proposed       | [#3](https://github.com/ethoxy/specs/issues/3) |
