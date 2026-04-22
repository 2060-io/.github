# 2060

**We build the open trust layer for the agentic internet.**

2060 is an independent research and engineering company inventing, specifying, and shipping the infrastructure that lets humans, services, and AI agents prove who they are and act under verifiable authority. Open source. Tallinn, Estonia. Founding member of the [Verana Foundation](https://verana.foundation).

- **Company** &rarr; [2060.io](https://2060.io) &middot; [contact](https://2060.io/contact)
- **Flagship product** &rarr; [Hologram](https://hologram.zone) &mdash; verifiable messaging for people, services, and AI agents
- **Neutral protocol** &rarr; [Verana](https://verana.io) &mdash; public trust registry, co-founded through the Verana Foundation
- **Open specs** &rarr; Verifiable Trust (VT) &amp; the Verifiable Public Registry (VPR)

<p align="center">
  <img src="assets/long-term2.svg" alt="Building for the long term" width="800" />
</p>

---

## The stack

### Hologram &mdash; consumer app and Verifiable Services

| Repository | Purpose |
| --- | --- |
| [hologram-app](https://github.com/2060-io/hologram-app) | Hologram mobile app (React Native). Live on App Store, Google Play, and Huawei AppGallery. |
| [hologram-server](https://github.com/2060-io/hologram-server) | Base backend for the Hologram app |
| [hologram-verifiable-services](https://github.com/2060-io/hologram-verifiable-services) | Reference Verifiable Services wrappers (Avatar, Passport, GitHub / X / Wise agents) |
| [hologram-generic-ai-agent-vs](https://github.com/2060-io/hologram-generic-ai-agent-vs) | Modular AI agent with LLM &middot; MCP &middot; RAG &middot; verifiable-credential auth, driven by a single `agent-pack.yaml` |
| [hologram-gov-id-issuer-vs](https://github.com/2060-io/hologram-gov-id-issuer-vs) | NFC passport &rarr; verifiable credential, with biometric liveness |
| [hologram-generic-verifier-vs](https://github.com/2060-io/hologram-generic-verifier-vs) | Generic Verifiable Credential verifier service |
| [hologram-concieragent-demo-vs](https://github.com/2060-io/hologram-concieragent-demo-vs) | Multilingual AI Travel Concierge (demo) |
| [hologram-liveavatar-agent-vs](https://github.com/2060-io/hologram-liveavatar-agent-vs) | Live-avatar AI agent (demo) |

### Protocols, SDKs, and primitives

| Repository | Purpose |
| --- | --- |
| [didcomm-mediator](https://github.com/2060-io/didcomm-mediator) | DIDComm mediator service |
| [webrtc-server](https://github.com/2060-io/webrtc-server) | WebRTC signaling for Hologram real-time calls |
| [react-native-eid-reader](https://github.com/2060-io/react-native-eid-reader) | NFC eID / ePassport reader native module for React Native |
| [vision-matcher](https://github.com/2060-io/vision-matcher) | Face-match and liveness (C++) |
| [credo-ts-didcomm-ext](https://github.com/2060-io/credo-ts-didcomm-ext) | DIDComm extension modules for [Credo](https://github.com/openwallet-foundation/credo-ts) |
| [credo-ts-didweb-anoncreds](https://github.com/2060-io/credo-ts-didweb-anoncreds) | AnonCreds method over `did:web` |
| [credo-ts-indy-vdr-proxy](https://github.com/2060-io/credo-ts-indy-vdr-proxy) | REST proxy for Hyperledger Indy ledgers |

### MCP servers

| Repository | Purpose |
| --- | --- |
| [mcp-wise](https://github.com/2060-io/mcp-wise) | Wise (TransferWise) MCP server for agentic payments |

---

## Timeline

|       |                                                               |
| ----- | ------------------------------------------------------------- |
| **2020**    | Verifiable Trust invented at the Internet Identity Workshop   |
| **2021–22** | First Hologram proofs-of-concept                              |
| **2023**    | Verana VPR development begins &middot; **2060 OÜ** founded in Tallinn |
| **2024**    | Verana Foundation co-founded                                  |
| **2025**    | Hologram live in market &middot; Verana Testnet                        |
| **2026**    | Hologram Cloud GA                                             |

---

## Get started

- **Try Hologram** &rarr; [hologram.zone](https://hologram.zone)
- **Read the docs** &rarr; [verana.io](https://verana.io) &middot; [verana.foundation](https://verana.foundation)
- **Meet us** &rarr; we present regularly at the [Internet Identity Workshop](https://internetidentityworkshop.com) and adjacent standards venues
- **Talk to us** &rarr; [2060.io/contact](https://2060.io/contact)

## License

Code published under this organization is licensed under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) unless otherwise noted in a given repository.

---

**2060 OÜ** &middot; Ahtri tn 12, 10151 Tallinn, Estonia &middot; Founded 2023 &middot; Registry 16853041 &middot; VAT EE102810457
