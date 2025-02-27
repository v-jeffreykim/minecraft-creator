---
author: v-josjones
ms.author: v-josjones
title: Item Documentation - minecraft:food
ms.prod: gaming
---

# Item Documentation - minecraft:food

`minecraft:food` sets the item as a food component, allowing it to be edible to the player.

## Parameters

|Name |Default Value  |Type  |Description  |
|:----------|:----------|:----------|:----------|
|can_always_eat|false |Boolean |If true, you can always eat this item (even when not hungry).|
|nutrition |*not set* | Integer| How much nutrition does this food item give the player when eaten.|
|effects |*not set* | List| List of Events to fire off when consumed|
|saturation_modifier|*not set* |String| Saturation Modifier is used in this formula: (nutrition * saturation_modifier * 2) when applying the saturation buff. Which happens when you eat the item.|
|using_converts_to| *not set* |String| When used, convert the *this* item to the one specified by 'using_converts_to'.|

## Example

```json
"minecraft:food":{
    "can_always_eat": false,
    "nutrition" : 3,
    "effects" : [
          {
            "name": "poison",
            "chance": 1.0,
            "duration": 5,
            "amplifier": 0
          }
    ],
    "saturation_modifier": "normal",
    "using_converts_to": "bowl"
}
```

## Vanilla entities examples

### appleEnchanted

:::code language="json" source="../../../../Source/VanillaBehaviorPack/items/appleEnchanted.json" range="13-43":::

## Vanilla entities using `minecraft:food`

- [apple](../../../../Source/VanillaBehaviorPack_Snippets/items/apple.md)
- [appleEnchanted](../../../../Source/VanillaBehaviorPack_Snippets/items/appleEnchanted.md)
- [baked_potato](../../../../Source/VanillaBehaviorPack_Snippets/items/baked_potato.md)
- [beef](../../../../Source/VanillaBehaviorPack_Snippets/items/beef.md)
- [beetroot_soup](../../../../Source/VanillaBehaviorPack_Snippets/items/beetroot_soup.md)
- [beetroot](../../../../Source/VanillaBehaviorPack_Snippets/items/beetroot.md)
- [bread](../../../../Source/VanillaBehaviorPack_Snippets/items/bread.md)
- [carrot](../../../../Source/VanillaBehaviorPack_Snippets/items/carrot.md)
- [chicken](../../../../Source/VanillaBehaviorPack_Snippets/items/chicken.md)
- [chorus_fruit](../../../../Source/VanillaBehaviorPack_Snippets/items/chorus_fruit.md)
- [clownfish](../../../../Source/VanillaBehaviorPack_Snippets/items/clownfish.md)
- [cooked_beef](../../../../Source/VanillaBehaviorPack_Snippets/items/cooked_beef.md)
- [cooked_chicken](../../../../Source/VanillaBehaviorPack_Snippets/items/cooked_chicken.md)
- [cooked_fish](../../../../Source/VanillaBehaviorPack_Snippets/items/cooked_fish.md)
- [cooked_porkchop](../../../../Source/VanillaBehaviorPack_Snippets/items/cooked_porkchop.md)
- [cooked_rabbit](../../../../Source/VanillaBehaviorPack_Snippets/items/cooked_rabbit.md)
- [cooked_salmon](../../../../Source/VanillaBehaviorPack_Snippets/items/cooked_salmon.md)
- [cookie](../../../../Source/VanillaBehaviorPack_Snippets/items/cookie.md)
- [dried_kelp](../../../../Source/VanillaBehaviorPack_Snippets/items/dried_kelp.md)
- [fish](../../../../Source/VanillaBehaviorPack_Snippets/items/fish.md)
- [golden_apple](../../../../Source/VanillaBehaviorPack_Snippets/items/golden_apple.md)
- [golden_carrot](../../../../Source/VanillaBehaviorPack_Snippets/items/golden_carrot.md)
- [honey_bottle](../../../../Source/VanillaBehaviorPack_Snippets/items/honey_bottle.md)
- [melon](../../../../Source/VanillaBehaviorPack_Snippets/items/melon.md)
- [mushroom_stew](../../../../Source/VanillaBehaviorPack_Snippets/items/mushroom_stew.md)
- [muttonCooked](../../../../Source/VanillaBehaviorPack_Snippets/items/muttonCooked.md)
- [muttonRaw](../../../../Source/VanillaBehaviorPack_Snippets/items/muttonRaw.md)
- [poisonous_potato](../../../../Source/VanillaBehaviorPack_Snippets/items/poisonous_potato.md)
- [porkchop](../../../../Source/VanillaBehaviorPack_Snippets/items/porkchop.md)
- [potato](../../../../Source/VanillaBehaviorPack_Snippets/items/potato.md)
- [pufferfish](../../../../Source/VanillaBehaviorPack_Snippets/items/pufferfish.md)
- [pumpkin_pie](../../../../Source/VanillaBehaviorPack_Snippets/items/pumpkin_pie.md)
- [rabbit_stew](../../../../Source/VanillaBehaviorPack_Snippets/items/rabbit_stew.md)
- [rabbit](../../../../Source/VanillaBehaviorPack_Snippets/items/rabbit.md)
- [rotten_flesh](../../../../Source/VanillaBehaviorPack_Snippets/items/rotten_flesh.md)
- [salmon](../../../../Source/VanillaBehaviorPack_Snippets/items/salmon.md)
- [spider_eye](../../../../Source/VanillaBehaviorPack_Snippets/items/spider_eye.md)
- [suspicious_stew](../../../../Source/VanillaBehaviorPack_Snippets/items/suspicious_stew.md)
- [sweet_berries](../../../../Source/VanillaBehaviorPack_Snippets/items/sweet_berries.md)
