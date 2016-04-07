---
layout: post
title: Powering the Connected Hiker
categories: [gear]
tags: [battery]
published: True

---

Modern technology has given us a lot of cool toys that can help us in the great outdoors. Some may stick to more classical, non-powered means, but for me, I like to use whatever tools are at my disposal. 

But to do that, I have a new limiting constraint to account for, that of powering my devices. This can get a bit complicated with all the choices of batteries and chargers, so below, I've broken down my process. 

## Gathering Requirements

First thing, I need figure out what needs to be charged. A battery is electrical power as bottles is to water. When we know how much water we drink per mile, and how many miles we need to hike between water sources, then we know how much we need to carry. 

So here are my electronics (or consumers of power)

- Phone - Nexus 5x (2700mAh) - USB-C
- Camera - Ricoh GR (1400mAh) - Proprietary 
- Camera - Theta S (1200mAh) - Micro USB

My longest carry should be about 5 days, or 130 miles, based on my planning. So from that I can try and figure out how many times I'll need to charge up those devices on the trail.

My phone is a fairly easy thing to estimate from experience. About every 2 days, I'll need a charge. This would mean that I'd need 2 charges while out on trail. 

- Nexus 5x - 2 x 2700mAh = 5400mAh

My cameras are suppose to each take about 400 shots per charge, and I normally average about a picture per mile (especially with that kind of mileage). So I'm unlikely to run out of power on them, but it's also probably true that if I run out of power, it's because the scenery is gorgous. So I will guesstimate a half charge on each camera. 

- Ricoh GR - 700mAh
- Theta S - 600mAh

Then we sum the usages up:

`54000mAh + 700mAh + 600mAh = 6700mAh`

We also have to add in an inefficency factor because not all the power from the battery pack will get to the devices. Some amount will be lost due to inefficencies, so a factor of 20% needs to be added. 

`6700mAh * 1.2 = 8040mAh` 

## Finding the Right Battery

I think it's important to learn how to read the specification for batteries when shopping for them.

1. Capactiy - How much power can the battery hold. 
2. Input - How fast can the battery be charged.
3. Output - How fast can the battery charge other devices. (Honestly, I don't care about this one) 
4. Weight - Because useless weight sucks.
5. Plug Types - What type of usb plugs go in to and out of the battery. 

### Capacity 
I know that I will need a capacity of `8040mAh` or more. This likely means 10000mAh as that is the next nearest tier.

### Input
This is, in my opinion, a very important field that should not be ignored. An analogy for this would be that we don't want to be using a gallon jug for carrying water if we have to fill it up with a teaspoon everytime. 

The standard is 5V/2A. A battery that can only take 5V/1A will take twice as long to charge up. 

#### Quick Charge
Quick charge lets a battery charge up at 9V/2A while the battery is below ~80%. Unless a product perfectly fits your needs (such as small battery packs), I would say Quick Charge is worth it.

Just be sure to check that the battery can be charged up with Quick Charge. Some batteries can only use Quick Charge when charging other devices.

*Even if you have an iPhone, which cannot use Quick Charge, the battery may be charged with Quick Charge, thus making it worth it for much faster charging in town.*

### Weight
The differences between battery packs of the same capacity are going to be minimal because ultimately, all of these battery packs need the same amount of batteries inside. Battery technology is a tough field right now and nobody has anything magical to dramatically reduce weight.

### Plug Type
I happen to be a bit special in that I have a USB-C phone. This is a new USB standard that is faster to charge which is good. But it also requires a different cable, so that is something that I kept in mind.

Most people just need Micro USB which is what the vast majority of batteries take as input/output.

## Finding the Right Charger
I found it a bit tricky to find the right charger because there is a lot of marketing words being used. 

### Number of Ports
This is the more obvious specification. Get the number of ports you realistically need. Remember that the battery pack will take a while to charge, so you could make due with fewer ports than devices if you are willing to cycle them as they get charged. 

### Output
The output from the charger is important in that it should match the max input the battery can take as input so that charging speed is maxed out. Most likely this will be 5V/2A or 5V/2.4A unless it has Quick Charge.

An important thing to note is that not all chargers will provide full power to all its ports. A lot of the smalle chargers will provide a total of 2.4A instead of 2.4A to each port. This could double the time it takes to charge the battery! 

### Quick Charge
If the battery takes Quick Charge, the charger needs to be able to provide it. Otherwise the fancy feature on the battery is worthless and likely adding extra weight.

## TL;DR; Recommendations

Part of the motivation for this post is that I've helped advice people several times on this topic already. And, unsurprisingly, I've noticed an emergent grouping.

Calculation help from [csgnetwork](http://www.csgnetwork.com/batterychgcalc.html).

### (Category - Weight - Charging Time)

### Light Usage (3350mAh) - 5oz - 4hrs

- [PowerCore+ Mini](http://www.amazon.com/dp/B005X1Y7I2) - 3oz
- Any 2 port charger - 2oz

### Medium Usage (6700mAh) - 7.5oz - 4hrs

- [RAVPower 6700 Battery](http://www.amazon.com/Portable-RAVPower-External-Technology-Smartphones/dp/B00Y2PX4U2) - 4.8oz
- [iClever 2 Port Charger](http://www.amazon.com/iClever-BoostCube-Technology-Blackberry-Bluetooth/dp/B00QTE09SY) - 2.9oz

### Heavy Usage (10050mAh) - 13.1oz (or 11.8oz) - 3.5hrs - Recomended 

- [PowerCore+ 10050](http://www.amazon.com/dp/B013HSQXZC) - 8.3oz

- [PowerPort+ 3](http://www.amazon.com/dp/B017JSZKGY) - 4.8oz
- [BlitzWolf 30W Qualcomm QC2.0 Dual USB](http://www.amazon.com/Charge-Charger-BlitzWolf-Qualcomm-Samsung/dp/B019H0JF3Q) - 3.5oz

### USB-C (10000mAh) - 12oz - 4hrs
USB-C plugs all around

- [iVoler 10000mAh External Battery Pack](http://www.amazon.com/iVoler-10000mAh-External-Battery-Charging/dp/B01A6HKP7E) - 8.3oz
- [Tronsmart USB-C Quick Charger, 2 Port](http://www.amazon.com/Charger-Tronsmart-Quick-Charge-Technology/dp/B019C23ZGW) - 3.7oz