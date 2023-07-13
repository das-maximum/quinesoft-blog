---
layout: post
title:  "RaspberryPi Feature Matrix"
date:   2023-06-09 12:00:00 +0200
tags: RasPi RaspberryPi
---

# RasperryPi Feature Matrix

This post contains a feature matrix of all RaspberryPis including the famous single board computers as well as the micro controller boards.

## Introduction

When searching for a micro controller to use for a simple thermometer, I was also taking a look at the Raspberry Pi Pico.
Having used a RaspberryPi 3+ and 4 already, I took a look at the micro controllers.
Unfortunately the [RasperryPi products page](https://www.raspberrypi.com/products/) does not contain a feature matrix.
So therefore I compiled one myself.

## Features of RasperryPi computers and micro controllers

| Name | Type | USB Ports | Ethernet | Wifi | Bluetooth |
| ---- | ---- | --------- | -------- | ---- | --------- |
| RaspPi&nbsp;1&nbsp;A+ | OBC<sup>1</sup> | 1x USB-A | no | no | no |
| RaspPi&nbsp;1&nbsp;B+ | OBC | 4x USB-A 2.0 | 100BaseT | no | no |
| RaspPi&nbsp;3&nbsp;A+ | OBC | 1x USB-A 2.0 | no | 802.11 b/g/n/ac | 4.2 BLE |
| RaspPi&nbsp;3&nbsp;B | OBC | 4x USB-A 2.0 | 100BaseT | 802.11 b/g/n | 4.1 BLE |
| RaspPi&nbsp;3&nbsp;B+ | OBC | 4x USB-A 2.0 | 1000BaseT (connected via USB 2.0) | 802.11 b/g/n/ac | 4.2 BLE |
| RaspPi&nbsp;4&nbsp;B | OBC | 2x USB-A 2.0<br />2x USB-A 3.0 | 1000BaseT | 802.11 ac | 5.0 BLE |
| RaspPi&nbsp;Zero | MC<sup>2</sup> | 2x Micro USB (one only for power) | no | no | no |
| RaspPi&nbsp;Zero&nbsp;W | MC | 2x Micro USB (one only for power) | no | 802.11 b/g/n | 4.1 BLE |
| RaspPi&nbsp;Zero&nbsp;2&nbsp;W | MC | 2x Micro USB (one only for power) | no | 802.11 b/g/n | 4.2 BLE |
| RaspPi&nbsp;Pico | MC | 1x Micro USB 1.1 | no | no | no |
| RaspPi&nbsp;Pico&nbsp;W | MC | 1x Micro USB | no | 802.11 n | no |

<sup>1</sup> One Board Computer  
<sup>2</sup> Micro Controller
