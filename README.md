# Open Access Media

> "Information is power. But like all power, there are those who want to keep it for themselves." — Aaron Swartz

A guide to building your own personal media server with Raspberry Pi and Jellyfin, plus a curated directory of free, legal, public domain content. Built for CPDJ 101 in the spirit of Aaron Swartz.

## What This Is

Streaming services are expensive, fragmented, and increasingly unreliable — content disappears overnight, prices rise every year, and your library is never really yours. This project documents an alternative: a self-hosted personal media server running free, open-source software on affordable hardware.

This repo contains:
- A complete step-by-step build guide for setting up a Raspberry Pi media server with Jellyfin
- A curated directory of free, legal, public domain media sources
- A single-page website (`site.html`) presenting all of the above

## Getting Started

Just open `site.html` in any browser. No build step, no dependencies, no installation required.

The site has three sections:
- **About** — the problem with streaming, the open access philosophy, and what we built
- **Build Guide** — step-by-step instructions from hardware setup to remote access
- **Resources** — curated links to free, legal media and open source tools

## The Build Guide Covers

1. Hardware & OS setup (Raspberry Pi Imager, Raspberry Pi OS Lite)
2. Remote access (SSH or Raspberry Pi Connect)
3. Installing Jellyfin
4. Accessing the Jellyfin UI
5. Adding media to your server
6. Watching your media on any device
7. Accessing your server outside your home (Tailscale)
8. Where to find legal, public domain content

## Tech Stack

**Website**
- React (via CDN, no build step)
- HTML/CSS

**Media Server**
- Raspberry Pi 4 or 5
- Raspberry Pi OS Lite (64-bit)
- [Jellyfin](https://jellyfin.org) — free, open-source media server
- [Tailscale](https://tailscale.com) — remote access

## Free Media Sources

A few of the sources catalogued in this project:

- [Internet Archive](https://archive.org) — movies, TV, audio, books
- [Librivox](https://librivox.org) — public domain audiobooks
- [Project Gutenberg](https://www.gutenberg.org) — free ebooks
- [NASA Media Library](https://images.nasa.gov) — photos and video
- [Free Music Archive](https://freemusicarchive.org) — openly licensed music

> **Note:** We only recommend using your media server with legally obtained or public domain content.

## Background

This project was built for CPDJ 101 and draws on the philosophy of Aaron Swartz, architect of Creative Commons and a founding figure of the Open Access Movement. His [Guerrilla Open Access Manifesto](https://archive.org/details/GuerillaOpenAccessManifesto) remains the clearest statement of why free access to information matters.

## Authors

Nikolas Posavec, Victor Olatunji, Felix Baum, Lucas Hufnagel, Rohan Gaddam
