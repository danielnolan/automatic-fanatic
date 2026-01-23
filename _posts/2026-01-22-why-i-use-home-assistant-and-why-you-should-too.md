---
layout: post
title: "Why I Use Home Assistant (And Why You Should Too)"
date: 2026-01-22
categories: [home assistant, smart home, privacy]
---

{% include youtube-embed.html id="SKPzojo2pwc" %}

I've been into home automation for quite some time now, and not that long ago I had a house full of Google and Nest devices. As with many people these days, my privacy concerns with these devices and big tech in general started to grow, and I knew there had to be a better way.

Enter Home Assistant.

## What is Home Assistant?

The [Home Assistant website](https://www.home-assistant.io/) describes it as open source home automation that puts local control and privacy first, powered by a worldwide community of tinkerers and DIY enthusiasts. This sounded exactly like what I wanted, so I downloaded it and installed it on an old computer I had laying around.

I was totally hooked from the minute I first logged in and saw the default dashboard. You can access the dashboard from any web browser, and they also have Android and iPhone apps. It didn't take me long to get my existing devices added via the included integrations, and I was well on my way to creating automations way beyond what you could ever hope to do with Google Home.

This was super cool, but I was still using devices like Nest Audio with Google voice assistant that was communicating with the cloud, which isn't cool at all when it comes to privacy.

## The Privacy Problem

Google, Amazon, and Apple have all had their share of privacy concerns and controversies. But these companies aren't the only ones with privacy issues. Every device you add in your home could be spying on you, intentionally or unintentionally.

One of the best things about running Home Assistant is it gives you the ability to control devices locally without the need for devices to be connected to the internet. Lots of enthusiasts strive to have little or no internet-connected devices, vastly increasing privacy. Over the past few years, I've used Home Assistant to build a smart home that I can trust, replacing cloud-connected devices with locally controlled ones.

## My Home Assistant Journey

My quest to replace cloud-connected devices led me to upgrade from running Home Assistant on an old PC to getting a [Home Assistant Yellow](https://www.home-assistant.io/yellow/), a device that was made by Home Assistant for running Home Assistant. Migrating to this device allowed me to leverage its built-in Zigbee controller and add a Z-Wave controller as well.

If you aren't familiar with Zigbee or Z-Wave, I'll cover them in detail in future videos. For now, just know that they are wireless protocols that allow for building mesh networks of smart home devices, and they are way better for battery-powered devices than regular WiFi.

Having the ability to use Zigbee and Z-Wave devices opened the door to a plethora of devices I could control locally:

- **Thermostat**: I replaced my cloud-connected Nest thermostat with a Z-Wave thermostat from Honeywell. Completely local controlled and can do anything the Nest could.
- **Door Lock**: I replaced the WiFi-connected Nest doorlock with a Z-Wave one from Yale, and holy smokes the batteries seem to last forever!
- **Cameras**: I've added cameras that don't have to connect to the internet, but I can access from anywhere.
- **Voice Assistants**: Google voice assistants have been replaced by local ones made by Home Assistant.

Don't get me wrong, I do still leverage some cloud-connected devices, but now it's a choice, not a requirement. That's the real beauty of controlling your home with Home Assistant. You can use whatever devices you want, cloud-connected or not. There are tons of integrations and detailed docs on making your own if one doesn't already exist for the device you're trying to control.

If you know how to code or have been thinking about tinkering, Home Assistant is written in the Python programming language and is the most popular open source project on the code collaboration site GitHub!

## How to Get Started

So now you're thinking all of this sounds great, but how do I get started? What if I don't have an old PC laying around?

**If you aren't super techy** and want the dead simple way to get started, I'd recommend getting a [Home Assistant Green](https://amzn.to/3ZkN6Rc). It comes with Home Assistant preinstalled and is pretty well plug and play.

**If you're a bit more advanced**, I'd probably get a mini PC to run it on like a [Beelink](https://amzn.to/3NpIMgV). This requires being comfortable with installing an operating system on a PC.

With either the Home Assistant Green or a mini PC, I'd recommend getting a Zigbee/Thread or Z-Wave coordinator from Home Assistant. They have just released the [ZBT-2](https://amzn.to/3NpIMgV) for Zigbee/Thread and the [ZWA-2](https://amzn.to/3ZkN6Rc) for Z-Wave and long range Z-Wave.

## My Current Setup

I've recently migrated my setup off of the Home Assistant Yellow to a server that I run in my mini home lab rack with all of my services in Docker containers. I like the control this gives me, and I've also learned a ton by configuring all of the services myself.

I leverage the new ZBT-2 and ZWA-2 controllers from Home Assistant for my Thread and Z-Wave devices these days. I've switched from Zigbee to Thread and Matter since they seem to be the future, and I was able to leverage a Zigbee to Matter bridge for the existing Zigbee devices I had. I'll cover these devices in detail in future videos.

Z-Wave is my preference so far for battery-powered devices as it's been super reliable, and long range Z-Wave works great over long distances and through walls. Everyone has different opinions on these wireless protocols and your mileage may vary.

## Why Home Assistant is the Clear Choice

For me, Home Assistant is the clear choice for the brains of our smart home:

- **Open Source**: Community-driven development with complete transparency
- **Privacy Focused**: Local control means your data stays yours
- **Device Freedom**: Works with whatever devices you want, cloud-connected or not
- **Hardware Flexibility**: Run it on anything from a Raspberry Pi to a full server

If you want to see the automations, devices, and services I use with Home Assistant to power our smart home, be sure to subscribe to my [YouTube channel](https://www.youtube.com/@AutomaticFanatic) and follow along!

---

*Some links in this post are affiliate links. If you make a purchase through these links, I may earn a small commission at no extra cost to you.*
