---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/Mojang/MinecraftScriptingApiDocsGenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: mojang-minecraft.WeatherChangeEventSignal Class
description: Contents of the mojang-minecraft.WeatherChangeEventSignal class.
---
# WeatherChangeEventSignal Class
>[!IMPORTANT]
>These APIs are experimental as part of GameTest Framework. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to GameTest Framework APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.


Manages callbacks that are connected to weather changing.


## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)
  
### **subscribe**
`
subscribe(callback: (arg: WeatherChangeEvent) => undefined): (arg: WeatherChangeEvent) => undefined
`

Adds a callback that will be called when weather changes.
#### Arguments
| Parameter | Type | Default Value | Description |
| :--- | :--- | :--- | :---: |
| **callback** | (arg: WeatherChangeEvent) => undefined | n/a | - |

Returns (arg: WeatherChangeEvent) => undefined


### **unsubscribe**
`
unsubscribe(callback: (arg: WeatherChangeEvent) => undefined): void
`

Removes a callback from being called when weather changes.
#### Arguments
| Parameter | Type | Default Value | Description |
| :--- | :--- | :--- | :---: |
| **callback** | (arg: WeatherChangeEvent) => undefined | n/a | - |


> [!WARNING]
> This function can throw errors.


