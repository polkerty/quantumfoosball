# Quantum Foosball (Foosenball)

Foosball, except the ball is a genuine quantum wavefunction.

A single self-contained HTML file. The ball is a complex wavefunction evolved by
the Schrödinger equation (split-step FFT); kicks are momentum boosts applied only
where the wave overlaps the strike. It disperses, diffracts around foosmen,
interferes with itself, and tunnels through thin defenses. Get ≥50% of the
probability into the far goal to score.

## Modes

- **1P vs the house** — local bot
- **2P same table** — shared keyboard or touchscreen
- **Open challenge (online)** — serverless P2P matchmaking via
  [Trystero](https://github.com/dmotz/trystero) (Nostr relay rendezvous, WebRTC
  gameplay). Both machines run the identical simulation in deterministic
  lockstep; only inputs cross the wire.

## Run

Open `index.html`, or serve the directory with any static file server.

Built with Claude Code.
