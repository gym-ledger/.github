# Gym Ledger

An open-source, self-hostable workout tracker for people who lift. Plan your week, log every set at the gym (with or without signal), and see your strength and body weight move over time.

<p align="center"><img src="https://raw.githubusercontent.com/gym-ledger/web/main/.github/assets/demo.gif" width="280" alt="Gym Ledger on a phone: home, progress, muscle map, body weight and logging a set"></p>

## Repositories

| Repo | What it is | Stack |
|---|---|---|
| **[web](https://github.com/gym-ledger/web)** | The app people train with. A mobile-first PWA that installs to the home screen and keeps working offline | Next.js 16 · React 19 · Tailwind CSS |
| **[api](https://github.com/gym-ledger/api)** | The REST API both apps talk to | Express 5 · TypeScript · PostgreSQL · Redis |
| **[admin](https://github.com/gym-ledger/admin)** | The admin panel for running an instance: exercise library, program builder, users and analytics | Next.js 16 · TanStack Table |

## Highlights

- **Logging built for the gym floor**: one exercise at a time, big numbers, a rest timer, warm-ups, drop sets and RIR
- **Offline-first**: sets logged with no signal sync when the connection comes back
- **Progress**: personal records, weekly volume, a muscle map, and body weight goals with a trend line
- **Private by default**: passwordless sign-in, a self-hosted CAPTCHA, data export and account deletion, and AI check-ins only if you opt in
- **Self-host in one command**: `docker compose -f stack/docker-compose.yml up --build` in the API repo starts everything. See [Run the whole stack](https://github.com/gym-ledger/api#run-the-whole-stack)

## Contributing

Issues and pull requests are welcome. Start with each repo's `CONTRIBUTING.md`, and report security problems privately as described in its `SECURITY.md`.

Built by [Mohit Chahal](https://github.com/itsmohitchahal).
