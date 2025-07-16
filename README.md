# U1253A/B Multimeter Battery Charger

## Overview

This device is a compact, thoughtfully designed battery charger made specifically for the U1253A and U1253B multimeters. Compared to the original OEM charger, it’s noticeably smaller and lighter, making it easy to carry in a tool bag or store in your workspace. It features a convenient USB Type-C input port, so you can power it with most standard phone chargers — no need for a bulky proprietary adapter.

---

## Smart Output Control

The charger is built for dependable operation with simple, reliable output management. By default, it starts up in an off state and requires a deliberate press-and-hold of the button for about ten seconds to enable charging when a load is present. An easy-to-read LED indicator shows the status at a glance: red when charging is active and green when the output is disabled.

---

## Automatic Shutoff and Protection

To help prevent accidental drain or misuse, the charger’s output will automatically turn off if it’s unplugged from the multimeter or if the meter’s knob is switched from the ‘off’ position. The charger also disables its output if the current drops below a preset threshold. This threshold is designed to detect conditions such as the charger being unplugged or a short circuit situation, like when the onboard polyfuse trips. This quick shutoff ensures the charger does not remain latched on unnecessarily and helps protect both the charger and the multimeter’s battery.

---

## Battery Compatibility

It’s important to ensure your multimeter is set up for the correct battery type before charging — the default setting is 7.2 volts, which works for a standard six-cell battery pack. If the battery is completely discharged — especially in the case of higher-capacity batteries — you may see a “charging error” message on the meter. Don’t worry: simply leave the meter on and connected, and the charger will continue to top up the battery. Once the minimum voltage level is reached, power cycle the meter and turn the charger back on — it will then complete the charging cycle normally.

---

## Key Features

- Compact package size compared to the OEM charger  
- USB Type-C input port for easy use with most phone chargers  
- Output short circuit detection and protection  
- User-selectable output with manual on/off latching control  
- Defaults to the off state when powered up for added reliability  
- Auto shutoff if unplugged, if the meter knob is switched, or if a short occurs  
- Red LED indicates active charging; green LED indicates output disabled  
- Supports batteries configured for 7.2V (6-cell pack)  
- Continues charging deeply discharged batteries until a safe voltage is reached

---

## Future Improvements

While this charger works reliably for its intended use, there are a few areas for improvement in future versions. The current design has thermal constraints — it was originally intended to operate without a heatsink, but during real-world use, a copper shim was needed to help dissipate excess heat. This adds complexity and cost. One practical solution for a future revision could be to use two converters working in tandem. This would reduce the thermal load on each converter and could actually lower overall costs by allowing the use of a less efficient (and more affordable) converter while maintaining safe operating temperatures and reliable performance.

Another area for possible improvement is support for USB Power Delivery (PD). This feature could allow the charger to negotiate a higher input voltage and current, improving efficiency and further reducing heat buildup. However, USB PD was intentionally omitted from the current design to maximize compatibility with basic phone chargers that do not support voltage negotiation. That said, by 2025, it has become increasingly rare to find USB-C chargers that lack PD capability — so adding PD support in a future version could deliver better thermal performance without sacrificing practical usability.

---

Compact, easy to power, and designed with practical features, this charger is a reliable upgrade for extending the life and convenience of your U1253 series multimeter — with clear room for even better performance down the line.
