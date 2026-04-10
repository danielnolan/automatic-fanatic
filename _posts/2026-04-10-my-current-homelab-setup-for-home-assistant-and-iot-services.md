---
layout: post
title: "My Current Homelab Setup for Home Assistant and IoT Services"
date: 2026-04-10
categories: [homelab, home assistant, networking, docker]
youtube_id: iCRHqslOrgA
---

{% include youtube-embed.html id="iCRHqslOrgA" %}

In this video I walk through the full homelab I've built to run my smart home — from the cable modem in the basement all the way to the mini server running Home Assistant and every other service in Docker containers.

## What's Covered

I go through every piece of hardware, how it all connects, and why I chose what I chose. That includes dual internet connections for redundancy, a dedicated firewall, a managed SDN network with multiple VLANs to keep IoT devices isolated, and the small-but-capable server that runs everything. My full Docker Compose setup is public on GitHub and linked in the video description.

## Gear Used

- **[DeskPi 10" Mini Rack](https://amzn.to/4sMyF5A)** — Compact rack in the office that houses the main switch, firewall, server, and NAS.
- **[Arris SurfBoard Cable Modem](https://amzn.to/4mf3ihE)** — Primary internet connection.
- **[AT&T Internet Air](https://www.att.com/internet/internet-air/)** — Fixed wireless backup connection for redundancy.
- **[Firewalla Gold SE](https://firewalla.com/products/firewalla-gold-se-firewall)** — Firewall and router with dual WAN failover and granular cross-VLAN firewall rules.
- **[TP-Link SG2008P (8-port PoE switch)](https://amzn.to/4cg64yK)** — Lives in the basement rack next to the modem.
- **[TP-Link ES205GP (5-port PoE switch)](https://amzn.to/4dvefJI)** — Behind the TV for a compact multi-port drop.
- **[TP-Link SG2210XMP-M2 (10-port managed switch)](https://amzn.to/3OnWFwS)** — The network backbone in the office rack, with 2.5G and 10G SFP+ uplinks.
- **[TP-Link EAP610-Outdoor](https://amzn.to/4sce1ur)** — Outdoor access point covering the yard and garden.
- **[TP-Link EAP610](https://amzn.to/3Q4AmwG)** — Indoor AP in the basement.
- **[TP-Link EAP660 HD](https://amzn.to/3PNO1IA)** — Main indoor AP for the living areas.
- **[Raspberry Pi 4](https://amzn.to/4ma5LKl)** with **[PoE HAT](https://amzn.to/4m9lidc)** — Runs the Omada SDN controller, powered directly from the switch.
- **[Minisforum MS-01](https://amzn.to/4sgyNt4)** — The main compute node running Debian Linux and all Docker containers.
- **[Minisforum N5 NAS](https://amzn.to/41gxZt6)** — TrueNAS for file storage and nightly backup target.

---

*Some links in this post are affiliate links. If you make a purchase through these links, I may earn a small commission at no extra cost to you.*
