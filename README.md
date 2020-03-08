<h1 align="center">

<img src="https://raw.githubusercontent.com/keesschollaart81/vscode-home-assistant/dev/assets/header.png" alt="Home Assistant Config Helper for Visual Studio Code"/>

[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/keesschollaart.vscode-home-assistant.svg "Current Release")](https://marketplace.visualstudio.com/items?itemName=keesschollaart.vscode-home-assistant)  [![Build Status](https://caseonline.visualstudio.com/vscode-home-assistant/_apis/build/status/keesschollaart81.vscode-home-assistant?branchName=master)](https://caseonline.visualstudio.com/vscode-home-assistant/_build/index?definitionId=23)

</h1>

# Getting started
      
1. Install via the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=keesschollaart.vscode-home-assistant)

2. Open your (local copy of the) Home Assistant Configuration with VS Code

3. Configure the connection to Home Assistant via the HA Section in the VS Code Settings UI
   
   More details in [the How-To in the Wiki](https://github.com/keesschollaart81/vscode-home-assistant/wiki/Configure-connection-to-HA)

4. Enjoy the features showcased below 👇

5. Continue reading in the Wiki:

    - [Configure connection to HA](https://github.com/keesschollaart81/vscode-home-assistant/wiki/Configure-connection-to-HA)
    - [VS Code Remote SSH](https://github.com/keesschollaart81/vscode-home-assistant/wiki/VS-Code-Remote-SSH)
    - [Your config, local or remote?](https://github.com/keesschollaart81/vscode-home-assistant/wiki/Your-config,-local-or-remote%3F)
    - [The troubleshooting guide](https://github.com/keesschollaart81/vscode-home-assistant/wiki/Troubleshooting)

# Features

## Completion for Entity ID's & Services

When connected with your Home Assistant server, entity id' and services will be auto-completed.
 
<img src="https://raw.githubusercontent.com/keesschollaart81/vscode-home-assistant/dev/assets/entity_service_completion.gif"   > 

## Completion & Validation for Configuration & Lovelace Schema

Most of the scheme's of Home Assistant will be validated and things like properties, values and enums will be auto-completed. This extension understands the behaviour of Home Assistant '!include...' behaviour and use this to provide scoped validation for all your files.
 
<img src="https://raw.githubusercontent.com/keesschollaart81/vscode-home-assistant/dev/assets/schema_validation_completion.gif"  > 

## Go to Definition for Includes

Easy navigate between your files references via the different !include... tags using 'f12' / 'Go to Definition'.
 
<img src="https://raw.githubusercontent.com/keesschollaart81/vscode-home-assistant/dev/assets/go_to_definition.gif"  > 

## Snippets

Snippets allow you to create commonly used data structures very quickly. 

<img src="https://raw.githubusercontent.com/keesschollaart81/vscode-home-assistant/dev/assets/snippet.gif"   > 

## Commands
Commands allow you to quickly interact with Home Assistant! Find them using Cmd+shift+P and type 'Home Assistant'

![image](https://user-images.githubusercontent.com/6755359/69496084-6b089d80-0ece-11ea-8496-50251b91732f.png)

# Contribution

- [How to update the schema's](https://github.com/keesschollaart81/vscode-home-assistant/wiki/HowTo:-Update-the-schema's)
- [Local Development](https://github.com/keesschollaart81/vscode-home-assistant/wiki/Local-development)

# Release Notes

Read all the recent changes in the [GitHub releases section](https://github.com/keesschollaart81/vscode-home-assistant/releases) 

# Feedback / Ideas

Create an [issue](https://github.com/keesschollaart81/vscode-home-assistant/issues/new/choose), reach out to me on [Twitter](https://twitter.com/keesschollaart) or the [Home Assistant Discord](https://discord.gg/c5DvZ4e).

# Things to do / up for grabs

- [ ] Go to Definition for entities, scripts and automations
- [ ] Render Jinja2 template locally (like/via CLI?) in preview pane 
- [ ] Autocomplete !secrets
- [ ] Autocomplete triggers
- [ ] Check local config with HA Server

# Build & Deployment status

|                     | Master   | Dev  |
|--------------------------------|-----------------|-----------------|
| Build status |  [![Build Status](https://caseonline.visualstudio.com/vscode-home-assistant/_apis/build/status/keesschollaart81.vscode-home-assistant?branchName=master)](https://caseonline.visualstudio.com/vscode-home-assistant/_build/index?definitionId=23)   | [![Build Status](https://caseonline.visualstudio.com/vscode-home-assistant/_apis/build/status/keesschollaart81.vscode-home-assistant?branchName=dev)](https://caseonline.visualstudio.com/vscode-home-assistant/_build/index?definitionId=23)
| Deployment Status | [![Deployment Status](https://caseonline.vsrm.visualstudio.com/_apis/public/Release/badge/b5e7419e-352f-433e-8690-463d52b2c4f7/1/2)](https://caseonline.visualstudio.com/vscode-home-assistant/_releases2?definitionId=1) |[![Deployment Status](https://caseonline.vsrm.visualstudio.com/_apis/public/Release/badge/b5e7419e-352f-433e-8690-463d52b2c4f7/1/1)](https://caseonline.visualstudio.com/vscode-home-assistant/_releases2?definitionId=1)|  
| Get it | [![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/keesschollaart.vscode-home-assistant.svg "Current Release")](https://marketplace.visualstudio.com/items?itemName=keesschollaart.vscode-home-assistant) | [![GitHub release](https://img.shields.io/github/release-pre/keesschollaart81/vscode-home-assistant.svg)](https://github.com/keesschollaart81/vscode-home-assistant/releases)|  
  
# Telemetry

This extension collects telemetry data to help us build a better experience for
using VS Code with Home Assistant. We use [vscode-extension-telemetry](https://github.com/Microsoft/vscode-extension-telemetry),
which reports the following data:

- Extension name
- Extension version
- Machine ID and session ID from VS Code
- Operating system
- Platform version

Additionally, if the language server fails to activate, we report the diagnostic
data the language server produces. The extension respects the `telemetry.enableTelemetry`
setting, which you can learn more about at VS Code's
[telemetry FAQ](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).
