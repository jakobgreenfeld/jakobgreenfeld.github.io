---
title: Two data sites I built
published: true
layout: post
permalink: 
excerpt: I crawled the homepages of the Inc 5000, YC, the Fortune 500 and unicorns, and the same tool turns out to have wildly different shares depending on which list you start from.
image: /images/default.png
categories: entrepreneurship, projects
---

I spent the last few weeks building two sites that do nothing but publish counts.

One is [Installmap](https://installmap.com/), which loads the homepage of every company on a named list and records which software the page loads.

The other is [FundingWatcher](https://fundingwatcher.com/), which holds startup funding rounds and the investors behind them.

Neither has a signup form and neither sells anything yet.

I wanted to find out whether a site that only publishes numbers, with the denominator printed under every one of them, gets read and cited.

The Installmap crawl covers six lists: the Inc 5000, Y Combinator, the Fortune 500, unicorns, a SaaS list and the Tranco top 10,000.

I expected the shares to be roughly similar across them, with the big lists just being bigger.

They are not close at all.

HubSpot runs on [25.6% of the crawled Inc 5000 domains and 2.5% of the Fortune 500](https://installmap.com/groups/inc5000_2026/hubspot).

That is 1,252 companies against 12.

OneTrust goes the other way, 44.9% of the Fortune 500 and 2.2% of YC companies.

PostHog is on [12.8% of YC company sites and 1.8% of the Inc 5000](https://installmap.com/groups/yc/posthog).

So when a targeting doc says "companies using HubSpot", the size of that market swings by a factor of ten depending on which list it was drawn from, and almost nobody selling technographics data says which list they drew from.

That was the finding that made me think the site was worth finishing.

On FundingWatcher the thing I did not expect came out of the YC data.

I embedded every YC company with a working domain, 6,142 of them across 48 batches, and measured how much each batch looked like what YC had already funded.

For batches between 2013 and 2019, 18.3% of a batch had a close match among a random sample of 500 earlier YC companies.

In Summer 2025 it was [46.5%](https://fundingwatcher.com/research/yc-batch-similarity/).

I went in assuming the answer would be a slow drift and instead the line breaks at Winter 2023 and never comes back down.

There is an obvious caveat, which is that the vectors describe each company as its website describes it today, so some of that is older companies drifting toward AI language after the fact.

I wrote that caveat into the report rather than leaving it out, because I would rather someone quotes the number with the caveat attached.

The investor side is the part I use most: 79,515 investor profiles, 24,254 of them venture capital firms, and 3,492 investors headquartered in London against 4,967 in New York.

Both sites are free to read and anyone can cite them.

If you find a number on either one that looks wrong, tell me and I will recheck the crawl.
