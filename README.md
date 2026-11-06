# Mohsin Hafeez

**AI-first Product Manager · Payments, Stablecoins & Core Infrastructure at [Fasset](https://fasset.com)**

I build products that move money, and the AI harnesses and agents that help teams build and run them.

<p align="left">
  <a href="https://linkedin.com/in/mohsin-hafeez" title="LinkedIn"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn" width="32" height="32" /></a>
  <a href="mailto:mosin.hafeez112@gmail.com" title="Email"><img src="https://cdn.simpleicons.org/gmail" alt="Email" width="32" height="32" /></a>
</p>

```mermaid
flowchart TB
    subgraph PM["PM one-shot harness"]
        direction LR
        A[Idea] --> B[Concept doc + JTBD] --> C[Behavior tree] --> D[Prototype] --> E[Eng-ready tickets]
    end
    subgraph SDLC["Agentic SDLC"]
        direction LR
        F[Agents build] --> G[Human review] --> H[Ship]
    end
    subgraph SWEEP["Treasury sweep agent"]
        direction LR
        I[Idle cash] --> J[Yield + arbitrage scan] --> K[Policy engine] --> L[Slack approval]
    end
    PM --> SDLC
    SDLC ~~~ SWEEP
```

---

### AI harnesses & agents

- **PM one-shot harness.** About 50 Claude skills that take an idea to a concept doc, a behavior tree, a clickable prototype and engineering-ready tickets in one pass. Open-sourcing it as `pm-harness` *(coming soon)*.
- **Agentic SDLC.** I helped define how product work feeds our engineering harness: concept docs, behavior trees and small outcome-based tickets that agents can build from, plus prototype-first handoffs.
- **Treasury sweep agent: `sweep-agent`** *(publishing soon)*. Finds idle cash across bank, exchange and wallet accounts and proposes ways to earn on it: stablecoin yield, tokenized treasuries, arbitrage. A policy engine enforces every limit, people approve in Slack, and every move is re-checked against fresh prices before it runs.

What I build and experiment with:

- **Agent skills** for Claude Code, Codex, Cursor and other coding agents
- **Always-on agents** that watch systems and get useful work done in the background
- **Multi-agent teams** for real workflows in research, finance, coding and design
- **Voice and browser agents, MCP apps and generative UI**
- **The reliability layer:** RAG, memory, evals and tool calling, the unglamorous parts that make agents dependable

How I work with AI:

- **Prototype first.** I connect our Figma design system to Claude Code, so designers and engineers start from a working prototype instead of a blank page.
- **Context in Git.** Product docs live in version control, where they're versioned and agents can read them.
- **Human in the loop for money.** Agents do the work, and a person approves anything that moves funds.

### Payments & stablecoins

- **$15M+ a month** in cross-border payouts across USD → PKR, BDT and NGN corridors
- **6 → 3 weeks** partner go-live, after I designed one shared integration layer that every payment and banking partner plugs into
- **4 payment and banking partners** integrated end to end: REST APIs, webhooks, transaction status lifecycles and payment orchestration through omnibus wallets
- **USD virtual IBANs** shipped, connecting UAE banking rails and local payment methods with global banking partners
- **Stablecoin settlement** infrastructure for GCC → APAC remittance corridors, linking fiat and on-chain flows, with **$1B+** in projected annual volume
- **Fasset Engine**, our B2B product: APIs and SDKs that let wallets, exchanges and fintechs embed digital-asset services ([docs](https://docs.fasset.com))
- **Liquidity dashboard and hedging workflow** for Treasury and FinOps, saving **15+ hours a month** in reconciliation and reporting

### Blockchain & DeFi

- **[Folks Finance](https://folks.finance)**: contributed to the lending and borrowing smart contracts on Algorand, written in Python (PyTeal), at Blockchain Italia
- **A51 Finance** (formerly Unipilot): owned the product vision and roadmap for this automated liquidity protocol for concentrated-liquidity DEXs, scaling it to **$1.5M TVL**. Improved execution efficiency by **8.5%** using Python and Rust
- **DeFi research**: analysed arbitrage transactions on Uniswap v2 and v3 using Etherscan and EigenPhi
- **[Decentralized voting dApp](https://github.com/Mosin112/Decentralized-Voting-Aapplication)**: time-based on-chain voting, built in React and deployed on Ethereum
- **[Self-sovereign zk identities](https://github.com/Mosin112/Self_Sovereign_zk_identities)**: research on self-sovereign identity models using zero-knowledge proofs
- **[origami-js-sdk](https://github.com/open-oracle-origami/origami-js-sdk)**: open-source contributor
- **IEEE BCCA 2024**: published a paper on digital assets, cryptocurrencies and blockchain

### Experiments & side projects

- **[axe.](https://www.axepayments.co)**: regulated crypto rails for Pakistan. One API that connects banks and fintechs to licensed crypto providers and local payment rails (RAAST, IBFT) for PKR on- and off-ramps, cross-border stablecoin transfers, smart routing, KYT screening and reconciliation. Partners hold the licences and custody; axe. orchestrates and never holds customer funds. In sandbox.
- **[Kapray](https://github.com/Mosin112/Kapray-app)**: a mobile app that brings Pakistani women's fashion brands into one feed, with alerts for new drops and sales. Expo, React Native, Supabase, and its own [scraper](https://github.com/Mosin112/kapray-scraper).
- **[HabitFlow](https://github.com/Mosin112/habitflow)**: an Android habit tracker built with Kotlin, Jetpack Compose, Room and Hilt.

### Languages and tools

**AI**

<p align="left">
  <a href="https://www.anthropic.com/claude" title="Claude"><img src="https://cdn.simpleicons.org/claude" alt="Claude" width="40" height="40" /></a>
  <a href="https://openai.com" title="OpenAI"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-png@2.6.0/dark/openai.png" /><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-png@2.6.0/light/openai.png" alt="OpenAI" width="40" height="40" /></picture></a>
  <a href="https://gemini.google.com" title="Gemini"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.102.0/icons/gemini-color.svg" alt="Gemini" width="40" height="40" /></a>
  <a href="https://z.ai" title="GLM (Zhipu AI)"><img src="https://cdn.jsdelivr.net/npm/@lobehub/icons-static-svg@1.102.0/icons/zhipu-color.svg" alt="GLM" width="40" height="40" /></a>
  <a href="https://modelcontextprotocol.io" title="Model Context Protocol"><img src="https://cdn.simpleicons.org/modelcontextprotocol/888888" alt="Model Context Protocol" width="40" height="40" /></a>
  <a href="https://www.figma.com" title="Figma"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" alt="Figma" width="40" height="40" /></a>
</p>

**Build**

<p align="left">
  <a href="https://www.typescriptlang.org" title="TypeScript"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" width="40" height="40" /></a>
  <a href="https://www.python.org" title="Python"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40" /></a>
  <a href="https://kotlinlang.org" title="Kotlin"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="Kotlin" width="40" height="40" /></a>
  <a href="https://www.rust-lang.org" title="Rust"><img src="https://cdn.simpleicons.org/rust/888888" alt="Rust" width="40" height="40" /></a>
  <a href="https://react.dev" title="React"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" width="40" height="40" /></a>
  <a href="https://nextjs.org" title="Next.js"><img src="https://cdn.simpleicons.org/nextdotjs/888888" alt="Next.js" width="40" height="40" /></a>
  <a href="https://nodejs.org" title="Node.js"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" width="40" height="40" /></a>
  <a href="https://expo.dev" title="Expo"><img src="https://cdn.simpleicons.org/expo/888888" alt="Expo" width="40" height="40" /></a>
  <a href="https://supabase.com" title="Supabase"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/supabase/supabase-original.svg" alt="Supabase" width="40" height="40" /></a>
  <a href="https://www.postgresql.org" title="PostgreSQL"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40" height="40" /></a>
  <a href="https://tailwindcss.com" title="Tailwind CSS"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" width="40" height="40" /></a>
  <a href="https://developer.android.com/compose" title="Jetpack Compose"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jetpackcompose/jetpackcompose-original.svg" alt="Jetpack Compose" width="40" height="40" /></a>
  <a href="https://developer.android.com/studio" title="Android Studio"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg" alt="Android Studio" width="40" height="40" /></a>
</p>

**Blockchain & payments**

<p align="left">
  <a href="https://soliditylang.org" title="Solidity"><img src="https://cdn.simpleicons.org/solidity/888888" alt="Solidity" width="40" height="40" /></a>
  <a href="https://ethereum.org" title="Ethereum"><img src="https://cdn.simpleicons.org/ethereum/627EEA" alt="Ethereum" width="40" height="40" /></a>
  <a href="https://algorand.co" title="Algorand"><img src="https://cdn.simpleicons.org/algorand/888888" alt="Algorand" width="40" height="40" /></a>
  <a href="https://tether.to" title="Tether (USDT)"><img src="https://cdn.simpleicons.org/tether" alt="Tether (USDT)" width="40" height="40" /></a>
</p>

Also: REST APIs & webhooks · SWIFT/ACH · bank integrations · stablecoin settlement · PyTeal · Uniswap v2/v3

**Data & delivery**

<p align="left">
  <a href="https://www.snowflake.com" title="Snowflake"><img src="https://cdn.simpleicons.org/snowflake" alt="Snowflake" width="40" height="40" /></a>
  <a href="https://mixpanel.com" title="Mixpanel"><img src="https://cdn.simpleicons.org/mixpanel" alt="Mixpanel" width="40" height="40" /></a>
  <a href="https://www.metabase.com" title="Metabase"><img src="https://cdn.simpleicons.org/metabase" alt="Metabase" width="40" height="40" /></a>
  <a href="https://www.atlassian.com/software/jira" title="Jira"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg" alt="Jira" width="40" height="40" /></a>
  <a href="https://www.atlassian.com/software/confluence" title="Confluence"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/confluence/confluence-original.svg" alt="Confluence" width="40" height="40" /></a>
  <a href="https://slack.com" title="Slack"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/slack/slack-original.svg" alt="Slack" width="40" height="40" /></a>
</p>

Also: SQL · Redshift

---

[LinkedIn](https://linkedin.com/in/mohsin-hafeez) · [mosin.hafeez112@gmail.com](mailto:mosin.hafeez112@gmail.com) · WAGMI
