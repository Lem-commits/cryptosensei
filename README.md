# CryptoSensei
![CryptoSensei logo](assets/logo.png)

AI character teaches crypto investing through short videos and on-chain trading simulations.

## Overview
CryptoSensei is an AI-generated character that explains investing and crypto basics in short-form videos for Instagram and TikTok, then invites viewers into a risk-free trading simulation game on Solana. Users earn NFT badges as they complete lessons and hit simulated trading milestones, creating shareable proof of learning.

## Problem
Investing education content is abundant but passive and often boring. Beginners aged 20-35 consume short-form video constantly, yet they have no safe way to practice trading before risking real money.

## Solution
CryptoSensei combines an engaging AI character video series with a gamified on-chain paper-trading simulator that rewards progress with collectible NFT badges, turning passive content consumption into active, provable learning.

## Features (MVP)
- AI character video generator for crypto/investing lesson scripts (text-to-video pipeline)
- On-chain simulated trading game using real-time price feeds (mock SOL/USDC balances)
- NFT badge minting on Solana when users complete a lesson module or trading milestone
- Leaderboard ranking simulated portfolio returns among friends and followers
- Shareable short video clips auto-generated from a user's simulation results for Instagram

## Tech Stack
- Solana Web3.js, Anchor
- Metaplex NFT
- Pyth price feeds
- ElevenLabs/TTS API
- Remotion or FFmpeg for video generation
- React / Next.js

## How It Works
```
[AI Lesson Video] --> [Viewer on IG/TikTok]
        |
        v
[Trading Simulator] --Pyth price feeds--> [Mock SOL/USDC balances]
        |
        v
[Milestone/Lesson Complete] --> [Anchor Program] --> [Metaplex NFT Mint on Solana]
        |
        v
[Leaderboard] + [Auto-generated shareable clip]
```
1. User watches a short AI-generated lesson video.
2. User plays an on-chain paper-trading simulation with real-time pricing.
3. Completing a lesson or milestone triggers an NFT badge mint on Solana.
4. Results appear on a leaderboard and can be shared as a short video clip.

## Roadmap
- Partner with crypto influencers to co-create AI character personas
- Add real yield/rewards for top simulated traders via sponsor pools
- Expand the badge system into a composable on-chain reputation/credential layer

## Pitch
See our full pitch deck at [docs/pitch.pdf](docs/pitch.pdf) and the spoken pitch script at [docs/pitch-script.md](docs/pitch-script.md).

## Team
- [Name] - Role (placeholder)
- [Name] - Role (placeholder)
- [Name] - Role (placeholder)

Built for the Colosseum hackathon (Solana and other chains).

---

🎬 Pitch video: [docs/pitch-video.mp4](docs/pitch-video.mp4)
