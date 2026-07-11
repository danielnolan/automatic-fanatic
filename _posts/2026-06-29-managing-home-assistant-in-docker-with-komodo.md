---
layout: post
title: "Managing Home Assistant in Docker with Komodo"
date: 2026-06-29
categories: [home assistant, docker, homelab, self-hosted]
youtube_id: LRU4oyQqdqY
---

{% include youtube-embed.html id="LRU4oyQqdqY" %}

Should you run Home Assistant in Docker? Is it hard? Can you still get the add-on experience? In this video I show how I run Home Assistant and all of its companion services in Docker, manage the whole thing from a clean web UI with Komodo, get update notifications right inside Home Assistant, and ping a private Discord channel whenever something goes sideways.

## What's Covered

I moved from HAOS to a Docker setup over the winter, and Komodo — an open-source, Git-driven container management platform — is what made it painless. I walk through the full stack running on my Home Assistant box, how radio sticks and Matter/Thread discovery work in Docker, deploying stacks straight from a Git repo with webhooks, and the two things that make it feel just like HAOS: update entities surfaced right on the Home Assistant dashboard through the Komodo HACS integration, and Komodo's built-in alerting piped to a private Discord channel.

If the only thing keeping you on HAOS is the one-click add-on experience, this setup gives you the same thing — with the entire Docker ecosystem available instead of a curated list, and your whole smart home version controlled in Git.

## Stacks Running in This Setup

Home Assistant Core • Z-Wave JS • Mosquitto MQTT • OpenThread Border Router • Matter Server • ha-mcp server • Grafana • VictoriaMetrics • Music Assistant • Cloudflared • Backrest (restic) • Traefik

## Links & Tools

- **[Komodo](https://komo.do)** — Open-source container management platform ([GitHub](https://github.com/moghtech/komodo)).
- **[Komodo Home Assistant integration](https://github.com/dkarv/ha-komodo)** — Surfaces stacks, containers, and update entities in Home Assistant (install via HACS).
- **[HACS](https://hacs.xyz)** — Home Assistant Community Store.
- **[Home Assistant](https://www.home-assistant.io)** — The brains of the whole thing.
- **[My full Docker homelab repo](https://github.com/danielnolan/docker_homelab)** — Every compose file, env, network, and volume from this setup.

---

*Some links in this post are affiliate links. If you make a purchase through these links, I may earn a small commission at no extra cost to you.*
