# Foundry Labs

Industrial AI infrastructure. Sensor to settlement.

We build the layer that lets AI agents read industrial equipment. Machines from
different manufacturers describe the same physical quantity in different words,
and that mismatch is where most industrial AI projects stall. Our work is to
remove it.

## Open

**[canonical-schema](https://github.com/FoundryNet/canonical-schema)**
The dictionary, published under MIT. 366 canonical fields and 16,908 vendor tag
mappings across 18 OEM families, covering CNC, robotics, additive, vehicle, and
AMR equipment. Free to embed, fork, or vendor.

## Products

**[Forge](https://foundrynet.io)**
The normalization kernel. 32 MCP tools over 14 protocols, translating raw
telemetry from 18 OEM families into one canonical vocabulary, then predicting,
diagnosing, and governing from it. Source is closed. See
[forge-mcp](https://github.com/FoundryNet/forge-mcp) for the MCP server.

**[Assay](https://assay.foundrynet.io)**
Agent identity and trust. Register an agent, build a verifiable track record,
and check reputation before delegating work.

**[MINT Protocol](https://github.com/FoundryNet/mint-mcp)**
Universal work attestation. Register, attest, verify, and discover autonomous
agents.

## Contact

[foundrynet.io](https://foundrynet.io) · forge@foundrynet.io · Reno, Nevada
