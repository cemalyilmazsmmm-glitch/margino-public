---
layout: post
title: "The Deli That Did the DoorDash Math (and Raised Its Delivery Prices)"
date: 2026-05-31
category: Deli Stories
author: Margino
description: A $12 chicken cutlet hero is a winner at the counter — and a near-loser on the apps. Here's the delivery-platform math every deli should run before it blames the slow month on rent.
---

The chicken cutlet hero is the pride of the deli. Pounded thin, fried to order, fresh mozz, roasted peppers, a little balsamic, on a hero that actually holds up. At the counter it's **$12**, and at $12 it's a good business: maybe **$4.50** in food cost, leaving real money on every one.

Then the deli put the menu on DoorDash and UberEats — because everyone said you have to — and listed the hero at the same **$12**. Orders came in. The kitchen got busier. And somehow the month still felt tight.

Here's why.

## The same sandwich, two very different businesses

A sale at the counter and a sale on the app are **not the same sale**. They just look the same on the menu.

**At the counter, $12:**

- Revenue: $12.00
- Food cost: $4.50
- **Left over: $7.50** (before labor/overhead — same for both, so we'll set it aside to compare apples to apples)

**On the app, also $12:**

- Platform commission (~30%): **−$3.60**
- Packaging (clamshell, bag, label): **−$0.60**
- Food cost: **−$4.50**
- **Left over: $3.30**

> Same sandwich. Same kitchen. **Less than half the margin** the moment it goes out as a delivery order. Sell enough of them at the wrong price and a "busy" month can make *less* than a slow one.

## The mistake isn't being on the apps — it's pricing them like the counter

Delivery customers already expect to pay more — that's baked into how the apps work, and every chain you order from does it. The deli's instinct to "keep prices fair and the same everywhere" is honorable, and it's quietly subsidizing DoorDash.

The fix is to **price the platform menu so that what's left after commission matches the counter.**

Run it backwards. You want about **$7.50** left over like the counter, after a ~30% cut and packaging:

- Target leftover + food + packaging = $7.50 + $4.50 + $0.60 = **$12.60**
- That's what you need to keep *after* commission. To net $12.60 after a 30% cut, list at about **$12.60 ÷ 0.70 ≈ $18.00.**

So the hero that's **$12 at the counter should be around $18 on the app** to be the same business. Even if you split the difference and list it at **$15.99**, you've recovered most of the margin instead of giving it away.

## Why most delis don't run this

Not because owners can't do arithmetic. Because the inputs move and live in different places:

- **Food cost** drifts every week as supplier prices change — and it's buried in paper invoices.
- **Commission rates** differ by platform and plan (DoorDash, UberEats, and Grubhub aren't identical).
- Nobody has time to redo this for **every item on the menu**, every time the cutlet supplier raises a nickel.

So the platform price gets set once, copied from the counter, and never revisited. That's the leak.

## What we built for this

Margino exists to make this calculation automatic. Snap the supplier receipt, and the cutlet, the cheese, the peppers, the bread land in **your own Google Sheet** with their real, current unit cost. From that, Margino suggests three prices for each item — **in-store, UberEats, and DoorDash** — each one built to protect the margin you actually want after that platform's cut.

You stop guessing whether the apps are helping or hurting. You can see it, per item, and price accordingly — the same day costs change, not at tax time when it's too late to fix.
