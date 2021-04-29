---
title: "Home Automation for Fun and Comfort Without Big Brother"
date: 2021-04-28T21:43:07-07:00
draft: true
---

Perhaps due to staying home too much, I have been tinkering with IoT (Internet of Things) devices - that by connecting to the internet, home devices can be easily customized for comfort and energy savings. We can then set up rules like turn off the AC and warn us if the door is left unlocked when we leave the house.

It is a fertile ground for new products, with every tech giant offering their unique yet monogamous solution. Their offering is quite similar in part due to their motivation beyond sales: these devices not only serve as gateways to other products (shop online, stream shows just by speaking), but also enable unprecedented access to personal data and behaviors. Through a myriad of sensors recording our every movement and conversation, this data collection helps improve services like personalized recommendations, further cementing the giants’ already entrenched dominance in our lives.

As consumers, we are presented with a trilemma: give up personal data, pay a premium for products that promise to be more privacy-conscious, or be denied this newfound convenience altogether. It doesn’t have to be this way. There are many free, open-source projects that offer similar convenience while allowing us to retain control over our own data:

- [Home Assistant](home-assistant.io/): A self-hosted home-automation app that controls and monitors IoT devices
- [Tuya-Convert](https://github.com/ct-Open-Source/tuya-convert): A tool that converts branded IoT devices to use custom firmwares without the need of physical intrusion
- [Tasmota](https://tasmota.github.io/docs/): A firmware that provides custom functionality to IoT devices

I’ll be writing a series of guides on how to hack our smart devices, build our own sensor networks, and set up central home automation for fun and comfort. By the end of the series, we will be able to control home devices from a smartphone or through automation, and visualize trends like temperature, all without exposing private data.

{{- $image := resources.Get "images/custom-sensor.png" -}}

{{- $image := resources.Get "images/tasmota-temperature-graph.png" -}}

Stay tuned.
