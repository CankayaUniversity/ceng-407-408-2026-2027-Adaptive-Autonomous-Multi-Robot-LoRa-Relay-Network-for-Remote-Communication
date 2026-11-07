# Adaptive Autonomous Multi-Robot LoRa Relay Network for Remote Communication

## Abstract
Establishing reliable communication in remote, disaster-stricken, or infrastructure-less environments is a critical challenge for emergency response and autonomous field operations. While Long Range (LoRa) radio technology provides low-power, long-distance communication, its physical layer performance is heavily degraded by non-line-of-sight (NLOS) obstacles, terrain elevation, and excessive distances. This study presents a review of an autonomous multi-robot relay system in which mobile ground robots ("car robots") dynamically reposition themselves to maintain and optimize a multi-hop LoRa mesh network between remote clients. The project examines the fundamentals of Mobile Ad-hoc Networks (MANETs) and algebraic connectivity maintenance, multi-hop LoRa mesh protocols (such as Meshtastic), lightweight publish/subscribe telemetry via MQTT, radio frequency (RF) site-planning propagation models, and adaptive positioning and path-planning algorithms. Furthermore, performance evaluation metrics, current hardware/protocol limitations, and future directions for self-healing robotic communication relays are discussed.

----

## 1. Introduction
Modern field operations—ranging from wilderness search and rescue (SAR) to subterranean exploration and post-disaster recovery—frequently occur in regions devoid of cellular coverage or fixed network infrastructure. In such scenarios, deploying a static wireless sensor network is often impractical due to unpredictable client movement and complex terrain geometry. Combining mobile robotics with low-power wide-area network (LPWAN) technologies offers a resilient alternative: an **Adaptive Autonomous Multi-Robot LoRa Relay Network**.

The primary objective of this system is to deploy autonomous ground vehicles equipped with LoRa transceivers that actively monitor link quality—such as Received Signal Strength Indicator (RSSI) and Signal-to-Noise Ratio (SNR)—and adaptively adjust their physical coordinates to bridge communication gaps between stationary or mobile client nodes. 
