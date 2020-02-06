# theguees
CodeFest-TheGuees

# Intro
This repo with shortcuts joins the Personal automation world of IOS and Iphones with the Networking world. We do this via a repo of commands or shortcuts that can not only turn lights on and off, but also allow the iPhone to query DNAC or Meraki directly, with voice commands or using inexpensive NFC tags.

Even with a locked iPhone, it's possible to query DNAC to get a status of DNAC devices. Siri will respond by speaking only the relevant content back to the user.

The phone acts as a client (like Postman or Python would) and is able to speak back the results. This is a great first step into managing networks with Natural Language Processing - NLP.

Another way to trigger the shortcuts is with NFC tags. Just by getting the phone closer to an NFC tag, we can trigger another shortcut that responds with the status of a critical endpoint (a critical Server, CEO's laptop, etc). The status could include Connection Type and status, location it's connected to including City and Country, and latest critical issues, among others.

# Requirements

- Any NFC Card (Try a hotel card, or an event badge)
- The Apple IOS Shortcuts app (https://apps.apple.com/us/app/shortcuts/id915249334)

# Steps

1. Download the DNAC Shortcut here: https://www.icloud.com/shortcuts/74d6b6b5921a4db1a9793f18850ab672

2. Download the Meraki Shortcut here: https://www.icloud.com/shortcuts/74d6b6b5921a4db1a9793f18850ab672
(This shortcut requires a Meraki API Key, a Meraki Vision Serial Number and a Image Recognition API Key from imagga.com (free))

To run the shortcuts, you may speak to Siri saying the exact title of the shortcuts, or if you want to use the NFC tag feature, you may run a shortcut by following this process:

1. Open the Shortcuts app
2. Click on the Automation Tab at the bottom
3. Click on the Plus (+) sign of the top right corner
4. Click on Create Personal Automation
5. Scroll down and click NFC
6. Click "Scan"
7. Bring the phone close to the NFC tag
8. Save your new automation.

