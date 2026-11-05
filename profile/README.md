<div align="center">

<img src="https://raw.githubusercontent.com/bitllm-org/branding/main/logo.svg" alt="BitLLM" width="128" height="128">

# BitLLM_

[![Website](https://img.shields.io/badge/bitllm.org-000000?style=flat-square&logo=safari&logoColor=white)](https://bitllm.org)
[![Install](https://img.shields.io/badge/install-000000?style=flat-square&logo=gnubash&logoColor=white)](https://github.com/bitllm-org/bitllm#install-and-run)
[![Source](https://img.shields.io/badge/source-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/bitllm-org/bitllm)
[![llms.txt](https://img.shields.io/badge/llms.txt-000000?style=flat-square&logo=markdown&logoColor=white)](https://bitllm.org/llms.txt)
[![MIT](https://img.shields.io/badge/license-MIT-000000?style=flat-square&logo=opensourceinitiative&logoColor=white)](https://github.com/bitllm-org/bitllm/blob/main/LICENSE)

</div>

---

## BitTorrent for local LLMs

**Share your local model, use everyone's.**

BitLLM is a peer-to-peer network for local LLM inference. Every node runs the same binary. Point
it at the OpenAI-compatible server you already use (vLLM, SGLang, llama.cpp, Ollama, LM Studio,
MLX), and it joins the network and gives you a local gateway at `http://127.0.0.1:7778`.

There is no coordinator. Peers find each other through a Kademlia DHT and gossip, connect directly
when they can, and go through relays plus hole punching when both sides are behind NAT. A request
goes to whichever peer serves the model you ask for. A model you share yourself is answered by your
own server and never leaves your machine.

Invite-only beta, MIT licensed. Using the network needs no account and no wallet.

## Open source

- [**bitllm**](https://github.com/bitllm-org/bitllm) - the node, local gateway, DHT, gossip,
  receipts, access rules, and dashboard.
- [**branding**](https://github.com/bitllm-org/branding) - the `BitLLM_` wordmark, PNG and SVG
  exports, colors, and usage.

## Start here

```bash
curl -fsSL https://bitllm.org/install.sh | sh
~/.local/bin/bitllm
```

Open `http://127.0.0.1:7778` for the dashboard. Agents can follow
[bitllm.org/llms.txt](https://bitllm.org/llms.txt) for the full setup.

## Read more

- [Use the network](https://github.com/bitllm-org/bitllm#use-the-network)
- [Share a model](https://github.com/bitllm-org/bitllm#share-a-model)
- [How access works](https://github.com/bitllm-org/bitllm#how-access-works)
- [Credits for serving](https://github.com/bitllm-org/bitllm#credits-for-serving)
- [What you should know](https://github.com/bitllm-org/bitllm#what-you-should-know)

---

<div align="center">

**Run a model. Use the network.**

[bitllm.org](https://bitllm.org) · [GitHub](https://github.com/bitllm-org/bitllm) ·
[Brand](https://github.com/bitllm-org/branding) · [llms.txt](https://bitllm.org/llms.txt)

</div>
