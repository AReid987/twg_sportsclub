# SPEC-001: TWG Sportsclub 🎟️

- [SPEC-001: TWG Sportsclub 🎟️](#spec-001-twg-sportsclub-️)
  - [Background 📚](#background-)
  - [Requirements 📝](#requirements-)
    - [Must Have 📌](#must-have-)
    - [Should have 🤔](#should-have-)
    - [Could Have 🔥](#could-have-)
  - [Method 👨‍🔧](#method-)
  - [Implementation 🔧](#implementation-)
  - [Milestones 🏆](#milestones-)
  - [Gathering Results 📊](#gathering-results-)
  - [C4 Model Description 📝](#c4-model-description-)
    - [Context Diagram 📈](#context-diagram-)

## Background 📚

TWG Sportsclub is a web application designed to offer users an engaging and competitive environment in which they can place picks on a variety of upcoming sporting events. By subscribing to the service, users receive virtual coins at the beginning of each month that they can use to place picks. The application features a real-time leaderboard to rank users based on the performance of their picks. Cash prizes are awarded to the top ranking users at the end of each month. This cycle renews monthly, resetting user coin balance to ensure a fresh start for all participants.

## Requirements 📝

### Must Have 📌

- Users can register to create an account
- Users can subscribe for a monthly fee.
- Registered users can log in, log out, view and edit their profile.
- Users can view their historical and pending picks.
- Users can view and interact with the real-time leaderboard
- Users can view data related to past and upcoming sporting events.
- Users can choose events, view odds, and pick a team or competitor to place a pick on.
- Users can view and track their winnings and losses.
- Monthly winners can withdraw their winnings.
- Users can pause or cancel their subscription.

### Should have 🤔

- Registered users can interact via a forum or messaging system.
- Users can view sporting events data to aid in placing wagers.

### Could Have 🔥

- User can view a sports news feed

## Method 👨‍🔧

## Implementation 🔧

## Milestones 🏆

## Gathering Results 📊

## C4 Model Description 📝

### Context Diagram 📈

- System: TWG Sportsclub 🏅
  - Primary Users
    - Players ⛹️‍♂️
    - Administrators 👮
  - External Systems 🧮
    - Supabase (for database) [text](https://supabase.com/docs) 🖥️
    - Supabase (for real-time Leaderboard data) [text](https://supabase.com/docs/guides/realtime) 📊
    - The Odds API (for sports events and odds data) [text](https://the-odds-api.com/) 🎟️
    - Stripe (for payment processing) [text](https://docs.stripe.com/api) 💳
    - Sports News API (for sports news, Provider TBD) 📰
    - Real-Time Scores API (for live event score updates, Provider TBD) ⏲️
      - LiveScore API ➡️ possible option [text](https://rapidapi.com/apidojo/api/livescore6)
    - Auth0 OR Supabase (for authentication) [text](https://auth0.com/docs) or [text](https://supabase.com/docs/guides/auth) 🔑
    - GitHub and GitHub Actions (for CI/CD pipeline) [text](https://docs.github.com/en/actions) 🔧
    - Nx Cloud (for remote caching and CI/CD optimization) [text](https://nx.app/) 🌩️
    - Deployment Platform (e.g., AWS, Azure, GCP, Vercel, Railway, Fly.io, etc) 🚀
