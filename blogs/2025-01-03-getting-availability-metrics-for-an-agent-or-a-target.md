---
title: "Getting availability metrics for an Agent or a Target"
url: "https://community.netbeez.net/t/getting-availability-metrics-for-an-agent-or-a-target/243#post_1"
date: "2025-01-03"
author: "@panickos Panickos Neophytou"
feed_url: "https://community.netbeez.net/posts.rss"
---
I’ve been asked a few times regarding retrieving the availability metrics for Agents and Targets in order to report them in third-party dashboards. Here’s how we calculate these metrics and how the get them through the API: Agent availability is the percentage of time the agent weas able to keep a steady connection to its BeezKeeper™ server. Target availability can be the reverse of packet loss from a Ping test that was running from multiple agents towards the target’s host.
