---
title: Use Amazon's Traffic to Drive DTC Sales - Product Idea
date: 2020-07-21T01:34:41.572Z
author: Matt Bahr
summary: Amazon has trumped Google as the end-all product search bar. Is a
  browser extension the answer to driving more direct DTC sales?
tags: []
---
In response to Bezos [casually snacking](https://twitter.com/NYDailyNews/status/1288607707101114368) during his congressional hearing yesterday and Shopify's GMV going [through the roof](https://twitter.com/jaminball/status/1288463895649116160), I'm hitting publish on a product idea I've had to help DTC companies drive traffic to their own storefronts from Amazon. And to preface, this is either a dumb idea... or sheer genius. I’m only one coffee in and am thinking the latter.

Amazon has become THE place to [search for products](https://www.retaildive.com/news/amazon-now-dominates-google-in-product-search/531822/). I've personally experienced the volume and exposure Amazon provides simply by listing your products on their platform -- it's wild. But with this new sales channel \[frenemy] comes its share of consequences. Most importantly, the brand no longer owns the customer relationship (goodbye first party data).

Back to the product idea... a few weeks ago, I was on Amazon searching for a massage ball. As I browsed Amazon product detail pages (PDPs) and reviews, I was intrigued by the fact that my instinct was to also go to the brand’s own DTC website to learn more (and deduce whether the product and brand were actually legit). It only took a simple Google search to find the brand and product I was looking at. The action I took here, looking at the brand’s own website, got me thinking. **Would it be possible to build a browser extension (a la [Honey](https://www.joinhoney.com/)) that simply mapped Amazon PDPs to DTC PDPs on brand websites, thus driving traffic from Amazon to the brand itself.** A lot to unpack here (see obstacles below) and previous to Honey's acquisition, I don't think this thought would have occured, but evidently a lot of people \[tens of millions] don't mind installing a browser extension. [nCage is still my favorite](https://chrome.google.com/webstore/detail/ncage/mpnfndnehgmmonhfcfdnaemdeokofgaf?hl=en).

## The Setup

Brands would sign up for an account and import a list of their PDPs (Shopify app?). Within the UI, they'd then match each owned PDP to the corresponding Amazon PDP and enter some general rules around discounts, pricing, and shipping. Quite simple to get started, and I’m sure a better-funded product could automate the process at some point.

As the product evolves, brands could also map other Amazon PDPs to their own products, thus making Amazon a source of attributable traffic and sales. An Adwords-like bidding system could be built, allowing brands to bid on various Amazon product pages.

## The UI

Similar to Honey's “discount available” pop-up, the UI would only need to contain a few items:

* **product pricing information**
* **a discount code (optional)** – ideally the brand is using Amazon 3p and not Amazon Retail, so they can control the pricing on their Amazon PDPs (if they have other wholesalers selling on Amazon this could be difficult)
* **estimated delivery timing** – ideally the brand can match Amazon Prime's "free" 2-day delivery (this one is a bit complicated in today's inventory management environment, another opportunity nonetheless)

Perhaps it would look like this (I'm no designer, [hit me up](https://twitter.com/mattrbahr) if you are, and want to take a crack at it):

![](/static/img/dtc-browser-extension.png "DTC browser extension example")

## Obstacles

* The biggest obstacle is the market: can we get consumers to see the value in installing a browser extension? Does the general consumer even care to buy direct, and if so, at what cost to the convenience of the almighty Amazon funnel? One timely go-to-market vector may be to focus on American-made products, given that 49% of the top 10,000 [Amazon.com](http://amazon.com/) sellers are based in China ([source](https://www.marketplacepulse.com/articles/chinese-sellers-outnumber-us-sellers-on-amazoncom))
* Amazon wouldn’t be a fan. If this gained traction, how would Amazon combat the extension?
* How would this work on mobile? Not sure about Amazon's latest desktop vs mobile/app traffic breakdown, but this may only cover a minority of Amazon's traffic.
* Availability. I mentioned this before, but complexities around inventory management would certainly come into play. Are we caching availability data for speed? What if a pop-up appears on an Amazon PDP and the item is no longer available?
* Would this train people to go to Amazon first to get a code, then buy from your brand?

## Upside

* Traffic, sales, greater margins (Amazon’s average rake is 30%)
* Brands would get more data on Amazon PDP views via users who have installed the app, and could then optimize copy, discount code, and shipping time?
* Potential for brands to finally gain access to the profile & data of their Amazon-bound shoppers
* Insight to the customer purchase journey: did they view on DTC website, then purchase on Amazon? Where should the attribution really land?