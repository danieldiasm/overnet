# OverNet

## An Override Network Framework for your Main Network

### About:

This is an IoT system that can be deployed in a way to override the main network equipment via an alternative connection (Phone data transmission, mobile internet, LoRa, etc).

The intended use is to add an administrative layer over a network or environment whenever there is no possible physical access at a given moment.

It should be possible to turn equipment on and off, reset things, have console access (via serial connection or network SSH). One of the features imagined is also having screen capture to control equipment that has a GUI too.

It is intended to be modular, so the main framework can be expanded with whatever equipment you have at hand, developing yourself or just configuring the ones available.

### Development Map for the base framework

- [ ] Initial Design Construction
- [ ] Feature Listing
- [ ] Feature Breakdown
- [ ] Feature Development Plan

### Add-on development

The framework should be agnostic to the IoT System that it is controlling or interacting with. So to help make this to be dettached from a specific type of IoT, Add-Ons can be developed, in order to increase capability of some IoT systems above the common ground shared between all of them.

### Initial Design - Base Roadmap
