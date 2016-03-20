# IoThingzBot

## About
Workshop Version:  Beta (March 2016)

Inspired--or perhaps troubled by--[Amazon's Dash button](http://www.amazon.com/oc/dash-button), which promises that you'll "never miss a beat" in the rhythms of consumption, this workshop seeks to cultivate literacy and agency in the emergent ecosystem of the "Internet of Things."

Specifically, we will leverage the physical computing simulation capabilities of [Autodesk's 123D Circuits](https://123d.circuits.io) and the web-based broker [IFTTT.com](http://ifttt.com) to create a Dash-like device that pleas on Twitter for the cloud to satisfy its most urgent desires for THINGZ.

The outputs of my bot can be viewed at <http://twitter.com/IoThingzBot>

## Activities

### First Steps

You will need to create a user account on the following sites to create your own IoT device.

* 123D Circuits:  <http://123d.circuits.io>
* IFTTT: <https://ifttt.com/join>

Optional (if you want to post to your own Twitter feed)

* Twitter:  <https://twitter.com/signup?lang=en>

### Basic Arduino Button to LED simulation

Duplicate this project:  [Basic Button to LED](https://123d.circuits.io/circuits/1805578-basic-button-to-led)

### Explore IFTTT recipes

1. Create a new IFTTT recipe at <https://ifttt.com/myrecipes/personal/new>
2. If This . . . Click "This" and find the Maker channel. Select it.
3. Set up a "Receive Web Request" trigger with Event Name "button_pressed"
4. . . . Then That:  Click "That" and find the Twitter channel.  Select it.
5. Connect the channel to your Twitter account.
6. Set up a "Post a Tweet" trigger with the following Tweet text:
```
Dear cloud: {{Value1}} here. I lust for {{Value2}}. Pls buy NOW or {{Value3}}!!!
```
7. Go to <https://ifttt.com/maker/> and click on the "How to Trigger Events" link where you can test out your Twitter setup.

### ESP8266 Stub

Duplicate this project:  [ESP8266 Stub](https://123d.circuits.io/circuits/1805945-esp8266-stub)
