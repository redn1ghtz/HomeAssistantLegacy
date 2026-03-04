# Home Assistant Legacy
* [Project description](#chapter-0)
* [Installation](#chapter-1)
* [Setting up](#chapter-2)
* [Description of functions](#chapter-3)
* [Bugs and new features](#chapter-4)

<a id="chapter-0"></a>
## Project description
**Home Assistant Legacy** - This is an application that supports older devices running iOS 9 and above to manage your server.

<a id="chapter-1"></a>
## Installation
[Download the latest release](https://github.com/redn1ghtz/HomeAssistantLegacy/releases/latest) and unzip the archive. Use AppSync or Sideloadly for installation!

<a id="chapter-2"></a>
## Setting up
1) Create a long-lived access token in yoour HA profile: Profile -> Long-lived Access Tokens -> Create Token.
2) Run application.
3) When you first launch the app, a setup screen opens. Enter the local IP address of the Home Assistant server in the first field. Enter the received Long-lived Access Token in the second field and click "Connect."
![SETUP](https://github.com/redn1ghtz/HomeAssistantLegacy/blob/main/Setup.jpg)
4) Done! You can now use the app.

<a id="chapter-3"></a>
## Description of functions
* All your devices will be displayed on the main screen.

* You can create your own dashboard:
1) Click "Dashboards" -> "+".
2) Enter the name.
3) Select devices to display in the dashboard.
4) Click "Save".

* You can change the order in which sensor groups are displayed:
1) Click "Order".
2) Change the order by dragging.
3) Click "Done".
4) Re-open the application.

<a id="chapter-4"></a>
## Bugs and new features

* Unfortunately, I couldn't make a camera, so I completely removed their support due to the old WebKit framework.

**If you find any bugs or devices that don't work, please create a report with this issue. I'll try to address it in new versions.**
