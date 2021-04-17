---
title: "Low Impact Website"
date: 2020-06-25
draft: false
tags: ["ecofriendly", "website", "conscious", "energy"]
---



I was inspired to switch to a low-impact, static-HTML website after [Organic Basics](https://lowimpact.organicbasics.com/usd), an underwear brand that sells eco-friendly TENCEL™ products, announced their release of a new Low-Impact Website option, which does not include videos and has very limited imagery. I know this is a really little change, and my site does not get many hits at all, but why not? *Why haven't you done this?* Read below to see just how much of an impact the internet has on the environment.

- [The internet (data centres, power plants, devices, transmission networks, etc) is responsible for about the same amount of carbon emissions as aviation (3%).](https://www.bbc.com/future/article/20200305-why-your-internet-habits-are-not-as-clean-as-you-think#:~:text=If%20we%20were%20to%20rather,of%20carbon%20dioxide%20a%20year)

- [An average website produces 1.76 grams CO2 per view.](https://www.websitecarbon.com/) 

- In 2016 it took [70 billion kilowatt-hours a year to run the internet.](https://www.forbes.com/sites/christopherhelman/2016/06/28/how-much-electricity-does-it-take-to-run-the-internet/#3ab4384c1fff), "to generate that amount of energy, you’d need to run power plants with a baseload capacity of 8,000 megawatts — equivalent to about 8 big nuclear reactors." 

- [By processing around 3.5 billion searches a day, google accounts for about 40% of the internet’s carbon footprint, an estimated amount of 500 kg of CO2 emissions per second.](https://qz.com/1267709/every-google-search-results-in-co2-emissions-this-real-time-dataviz-shows-how-much/)

- [The covid-19 pandemic caused internet usage to increase by around 70%.](https://www.statista.com/statistics/1106607/device-usage-coronavirus-worldwide-by-country/)

- More information can be found [here](https://www.bbc.com/future/article/20200305-why-your-internet-habits-are-not-as-clean-as-you-think#:~:text=If%20we%20were%20to%20rather,of%20carbon%20dioxide%20a%20year), [here](https://theshiftproject.org/en/article/unsustainable-use-online-video/), and [here.](https://theicct.org/publications/co2-emissions-commercial-aviation-2018)


At the bottom of this page there is a "Website Carbon Badge," created by [Whole Grain Digital](https://www.wholegraindigital.com/) that automatically calculates and displays the carbon emissions of the page. The badge itself does impact on carbon emissions and because of that it has been designed to be as "lightweight" as possible. However, it is a good reflection on how much carbon is actually produced every time someone visits a web page.

- [For a website with 10,000 monthly page views, it is responsible for 211 kg of CO2 emissions per year. This is approximately the same amount of carbon that 1 tree absorbs in a year.](https://www.websitecarbon.com/website/alexandriaahluwalia-netlify-app/)

- You can check how *your* website is impacting the planet (through an approximation of carbon emissions by considering the amount of data transfer over the wire, energy intensity of web data, energy source used by the data centre, carbon intensity of electricity, and website traffic) [here.](https://www.websitecarbon.com/)


To create a low-impact website, I chose to create a static [Hugo](https://gohugo.io/) site (static HTML), use [Netlify](https://www.netlify.com/) for hosting*, and I followed some guidelines on [building low impact websites](https://gomakethings.com/building-low-impact-websites/). This Hugo layout is designed by [VarKai](https://varkai.com/), is really easy to modify/manage, and most importantly, is really low impact. To support my projects and showcase my work, but to be conscious of the impact of them, I will try to limit the use of images and graphics. If you would like to see a demo please send me an [email](mailto:lexi.ahluwalia@gmail.com).


<div id="wcb" class="wcb carbonbadge"></div>
<script src="https://unpkg.com/website-carbon-badges@^1/b.min.js" defer></script>

*Netlify is not a "green" host, if I used a "green" host my emissions would be 9% less. Most "green" hosts charge more than I want to pay to host my site, also, I know I don't get many hits. So my impact is still a lot less than a site with, let's say, 10,000 visits/month. However, highly recommend [Netlify](https://www.netlify.com/). Their customer service is amazing, it works well with GitHub, and it is free for individual users. 
