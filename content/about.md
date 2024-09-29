---
title: "About Me"
author: "dragsbruh"
date: "2024-09-29"
description: "Who even is writing all this? Although theres nothing written? Good question."
series: ["Me"]
aliases: ["info"]
ShowToc: true
TocOpen: false
weight: 2
layout: "page"
cover:
  image: images/posts/cage.png
  caption: "Tatakae, Eren."
---

## Hi there hello

I am dragsbruh, I'm a student who does stuff related to computers and the internet. I barely have free time.

Heres a progress bar that tells when I'm finally gonna be a free.

{{< rawhtml >}}
<progress id="timebar" value="100" max="100" style="width: 100%;"></progress>
<sup><i>total: <strong>2 years</strong></i> (<span id="timebar-value"></span>)</sup>

<script>
    function doPercentageTime(start, end) {
        const now = Date.now();
        const totalDuration = end - start;
        const elapsed = now - start;
        return Math.floor((elapsed / totalDuration) * 100);
    };
    let percentage = doPercentageTime(1717558200000, 1780673400000);
    document.getElementById("timebar").value = percentage;
    document.getElementById("timebar-value").innerText = `${percentage}% complete`;
</script>

{{< /rawhtml >}}

## Interests

I have a ton of interests so heres a few of them

- Rocket League
- Peer to peer networking
- Onion Router (tor)
- Malware Development
- Backend Development
- More Backend Development
- Automation (partially)

## What I'm working on

At the time of writing this, I am working (or planning on working) on a few things:

- Decentralized social network
- Tor-based fully private chat app (maybe merged with the decentralized social network, or one of them might be removed in favor of the other)
- A small terminal based music player
- A chunked cloud based file storage system
- A reverse proxy service
- A file server

> Ah, college, good old friend. I paused some of these projects because of college.

## Tech Stack

See what tools and infra I use [here](/tools/)

## Plans for future

I kinda dislike working at big companies because, at least now, most of them (not all) seem pretty bad. I think I’ll focus on my own projects and work at a few startups until I start my own or something.

I haven't really decided on a field yet, but if I had to, then I would pick backend or red teaming.

## Bye~

{{< rawhtml >}}
<progress id="timebar2" value="100" max="100" style="width: 100%;"></progress>
<sup><i>total: <strong>28 years</strong></i> (<span id="timebar2-value"></span>)</sup>

<script>
    let percentage2 = doPercentageTime(1230532200000, 2114145000000);
    document.getElementById("timebar2").value = percentage2;
    document.getElementById("timebar2-value").innerText = `${percentage2}% complete`;
</script>

{{< /rawhtml >}}
