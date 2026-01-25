---
layout: post
title: "Running Ethernet to My Home Office: Relocating the Server Rack"
date: 2025-12-28
categories: [networking, diy, behind the scenes]
featured_image: /assets/images/posts/ethernet-office/IMG_2892.jpg
---

My home automation setup had a problem: the only ethernet port in my house was in the living room. That's where I had my mini rack with the Home Assistant server and my new NAS. But having server equipment humming away next to the couch wasn't ideal, and I needed proper connectivity in my office anyway.

Time for a weekend project: run ethernet to the office and relocate everything.

## The Plan

The goal was simple but involved a few steps:

1. Cut a hole in the office wall for a new ethernet jack
2. Run CAT6 cable from the office down to the basement
3. Install a proper wall plate with two ports - one for the Starlink connection and one running to the basement rack
4. Relocate the mini rack to the office
5. Move the original network equipment to the basement

## Materials

Here's what I picked up for the job:

![Networking materials laid out](/assets/images/posts/ethernet-office/IMG_2892.jpg)

- PPC Perfect Link CAT6 cable (750ft box - way more than needed, but good to have on hand)
- Low voltage mounting bracket (old work box)
- Dual-port keystone wall plate
- CAT6 keystone jacks
- My trusty DYMO Rhino label maker

## Cutting the Wall

First step was cutting the hole for the low voltage box. I picked a spot behind where the desk would go, measured twice, and cut once.

![Hole cut in the wall](/assets/images/posts/ethernet-office/IMG_2890.jpg)

Pro tip: Use a low voltage "old work" bracket for this. Unlike electrical boxes, these don't need to be attached to a stud - they clamp right onto the drywall. Perfect for running data cables.

## Running the Cable

With the hole cut, I ran two CAT6 cables - one would connect to the Starlink router, and the other would run down to the basement where I was relocating some network equipment.

Labeling your cables is crucial. I use a DYMO Rhino for this - it prints on actual cable labels that wrap around and won't fall off.

![Making cable labels](/assets/images/posts/ethernet-office/IMG_2893.jpg)

## Terminating the Jacks

This is where attention to detail matters. CAT6 keystone jacks are color-coded, so you just need to match the wire colors to the diagram on the jack. I use the T-568B standard.

![Wiring the keystone jack](/assets/images/posts/ethernet-office/IMG_2894.jpg)

Punch down each wire, trim the excess, and snap it into the wall plate.

![Wall plate with labeled jacks](/assets/images/posts/ethernet-office/IMG_2895.jpg)

Both cables labeled and terminated - STARLINK for the internet connection and BASEMENT for the run down to the network rack.

## Installing the Wall Plate

With the cables terminated, I mounted the low voltage bracket and installed the wall plate.

![Cables running through the wall](/assets/images/posts/ethernet-office/IMG_2900.jpg)

![Low voltage box installed](/assets/images/posts/ethernet-office/IMG_2901.jpg)

The finished wall plate looks clean and professional:

![Finished ethernet wall plate](/assets/images/posts/ethernet-office/IMG_2902.jpg)

## The Basement Side

Down in the basement, I terminated the other ends of the cables and organized everything at the new rack location. While I was at it, I also ran a cable for the garage camera.

![Labeling garage camera cable](/assets/images/posts/ethernet-office/IMG_2903.jpg)

Labeling every cable at both ends saves so much troubleshooting time later. Trust me on this one.

## The Final Setup

With all the cables run and terminated, I moved the mini rack to its new home in the office:

![Final office setup with server rack](/assets/images/posts/ethernet-office/IMG_2957.jpg)

The setup now includes:
- **Starlink router** - Providing internet to the whole house
- **Mini server rack** - Housing the Home Assistant server and NAS
- **Network switch** - Connecting everything together
- **3D printer** - Because why not?

Everything is now in one spot, easy to access, and not cluttering up the living room anymore.

## Lessons Learned

1. **Label everything** - Seriously, label both ends of every cable
2. **Buy more cable than you need** - Running short mid-project is frustrating
3. **Use proper low voltage boxes** - They make the install look professional
4. **Take your time with terminations** - A bad crimp means troubleshooting later
5. **Plan your cable routes** - Think about where you might want to run cables in the future

This project took about half a day and made a huge difference in my home network setup. If you're running ethernet in your house, don't be intimidated - it's very doable as a DIY project.

Have questions about running ethernet or setting up a home server rack? Drop a comment on the YouTube video!
