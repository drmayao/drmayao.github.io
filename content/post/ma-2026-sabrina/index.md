---
title: "Bose Noise Cancelling Wired Earbuds: bringing ANC back to a wired form factor"
summary: "A personal note on the launch of Bose Noise Cancelling Wired Earbuds and the acoustic and algorithmic work behind their active noise cancellation."
date: '2026-10-02'
lastmod: '2026-10-02'
draft: false
featured: false
authors:
  - admin
tags:
  - Bose
  - Active Noise Cancellation
  - Acoustics
  - Audio DSP
categories:
  - Products
---

I am excited to see the **Bose Noise Cancelling Wired Earbuds** announced. I led the design of the active noise-cancellation (ANC) algorithm for this product, and it has been especially rewarding to help bring a familiar, simple listening format into a new technical space: USB-C wired earbuds with active noise cancellation and no battery to charge.

ANC in a compact earbud is an acoustic-system problem as much as an algorithm problem. The cancellation path depends on the transducer, microphones, ear-tip seal, and the listener’s fit—each of which can change the response the algorithm sees. The work involved repeated measurement and listening cycles to tune the trade-offs among attenuation, stability, audio fidelity, transparency behavior, and a robust experience across real-world fits and environments. The final product uses four microphones—two in each earbud—for Bose QuietControl noise cancellation, with Quiet, Aware, and ANC-Off listening modes.

The earbuds connect through USB-C, draw power from the source device, and support plug-and-play audio without Bluetooth pairing or a companion app. Bose announced the product on September 28, 2026, at a U.S. price of $99; shipments are scheduled to begin October 15. The official announcement has the [full product details and specifications](https://www.bose.com/pressroom/bose-unveils-new-noise-cancelling-wired-earbuds).

It is gratifying to see early coverage engage with the engineering intent. In an [early listening report](https://www.wired.com/story/bose-to-release-wired-headphones-after-10-years/), WIRED wrote that “the noise canceling is a godsend.” In [Bloomberg coverage by Chris Welch](https://www.bloomberg.com/news/articles/2026-09-28/bose-debuts-99-bose-noise-cancelling-wired-earbuds-seizing-on-growing-trend), early hands-on use found that the earbuds could still reduce the level of noise on a New York subway car and in a crowded café, while placing their cancellation below higher-priced wireless flagships.

I am grateful to have worked with a talented cross-functional team on a product that makes careful acoustic and DSP work feel straightforward for the listener: plug in, press play, and focus on the sound.
