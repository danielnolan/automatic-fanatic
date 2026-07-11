---
layout: post
title: "Automating Fertigation with a Zooz LR Z-Wave Relay"
date: 2026-05-07
categories: [home assistant, z-wave, automation, irrigation]
youtube_id: cfcFt1_AwS8
---

{% include youtube-embed.html id="cfcFt1_AwS8" %}

Last year I added automated drip irrigation to our vegetable garden along with an EZ-FLO fertilizer injector for fertigation — the only problem being that the injector wasn't actually automatic. In this video I fix that, making the EZ-FLO truly hands-off with a Zooz LR Z-Wave relay, a 12-volt power supply, and two quarter-inch solenoid valves, all wired into a custom 3D-printed enclosure and controlled through Home Assistant.

## What's Covered

I walk through the whole build: the parts, why normally closed solenoid valves matter for safety, wiring both valves in parallel off the ZEN58 dry contact relay, tidying everything into a printed enclosure with cable glands and lever wire connectors, and installing the valves on the EZ-FLO's inlet and outlet lines. On the software side, the relay pairs to Home Assistant over Z-Wave JS with SmartStart, giving you a single switch entity to schedule or automate however your garden needs — layering fertigation on top of the moisture- and weather-based watering automation I already run.

## Products Used

- **EZ-FLO Premium Lawn and Garden Feeder** — Inline fertilizer injector that mixes nutrients into your irrigation water.
- **[Zooz ZEN58 Low Voltage XS Relay](https://amzn.to/4duz0EJ)** — A tiny Z-Wave Long Range dry contact relay (9–40V) that switches both valves.
- **[Waterproof 120V AC to 12V DC Power Supply](https://amzn.to/4nj2usD)** — Powers the relay and both valves from one source.
- **[1/4" Quick Connect Normally Closed Solenoid Valves](https://amzn.to/42oDFSr)** — Fail-shut valves for the inlet and outlet lines.
- **[2-in, 8-out Lever Wire Connectors](https://amzn.to/42R6xCX)** — Make the parallel wiring dead simple.
- **[Customizable 3D-Printed Project Enclosure (MakerWorld)](https://makerworld.com/en/models/952727-customizable-project-enclosure-box?from=search#profileId-1942731)** — Sized to fit the relay, power supply, and connectors.

Everything integrates directly with Home Assistant through Z-Wave JS — local, no cloud required.

---

*Some links in this post are affiliate links. If you make a purchase through these links, I may earn a small commission at no extra cost to you.*
