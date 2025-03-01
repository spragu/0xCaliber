# 0xCaliber
![DALL·E 2025-02-26 12 19 35 - A powerful illustration of a rifle embedded in stone, with its barrel pointing towards the ground, inspired by the Excalibur sword in the stone  The r (2)](https://github.com/user-attachments/assets/765c9090-8c93-4434-970b-3476e80db0ee)

# Software Engineer
Christopher Sprague
Discord: cspragu

# Business & Communications
Alex ___
ContactHere: ____



0xCaliber is a multiplayer first-person shooter that blends classic FPS action with cutting-edge blockchain technology. In this game, every bullet is more than just ammo—it’s an investment. Players buy bullets through a smart contract, locking in their resources before entering intense, fast-paced battles. With its unique pay-to-play model and integration across multiple blockchains, 0xCaliber offers a fresh, strategic twist on gaming. Get ready to aim, shoot, and win crypto across various participating blockchains.

---
Unity game repo: https://github.com/spragu/0xCaliber-game-ethdenver-2025\
---
---
Companion app: https://github.com/spragu/0xCaliber-Companion
---

## Bounties & Objectives

Below is an overview of the key bounties we are targeting, along with the rationale behind each and how we plan to implement the technology:

| **Bounty Category**               | **Reason/Impact**                                          | **Technology Implementation**                                   |
|-----------------------------------|------------------------------------------------------------|-----------------------------------------------------------------|
| **ZKsync: Best Web3 Onboarding UX using Smart Sign-On (SSO) SDK**          | Top level account id backed by passkey. Useful because it can aggregate many wallets and other subidentities           | Companion app (wagmi) where users can register their master account     |
| **Build a mass consumer dApp fully on-chain, Create something new only possible with Somnia**          | We wanted a way to interact with our smart contracts to log bullets fired as fast as possible for usage in an anticheat/play verification system           | Websocket emitting events logging bullets fired on the chain.      |
| **Only possible on ICP**          | We need a way to externally control the global regen/degen mode of the game in a decentralized manner. We were also planning on working in secure randomness on each subsequent timer invocation but ran out of buidl hours.           | ICP canister running global timer on an interval and alternating the isDegenMode bool that is publicly exposed in the canister for http calls so the unity game can poll degen/regen mode      |

---

## Mission

### Hackathon Mission
Our primary goal during the hackathon is to show a proof of concept of a realtime and fun 3d blockchain game which is pay to play but skill based earnings instead of scheduled/login reward based..

### Beyond the Hackathon
0xCaliber is not just a hackathon project—it’s a vision for the future of gaming. Our long-term mission includes:

- **Hardening:** There are numerous parts of the contracts that require trust. We are trying to work through this with a well thought solution using merkle trees.
- **Enhancing the UI/UX:** The ui/ux experience is weak at best and honestly incomplete in some areas. We just did not have enough man hours to cover all of the corners in order to make something that is truly production worthy during the hackathon.

---
