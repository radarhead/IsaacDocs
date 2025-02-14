# Class "TemporaryEffects"
## Functions
### Add·Collectible·Effect () {: aria-label='Functions' }
[ ](#){: .rep .tooltip .badge }
#### void AddCollectibleEffect ( [CollectibleType](../rep/enums/CollectibleType) CollectibleType, boolean AddCostume = true, int Count = 1 ) {: .copyable aria-label='Functions' }
Adds the effect of a collectible to the player, without actually giving him the assosiated item.

???+ bug
    This function does only work for some collectibles, but not all. For example, it doesnt work for "Chocolate milk".

???- example "Example Code"
    This code applies the effect and costume of the item "Sad Onion" to the player.

    ```lua
    local player = Isaac.GetPlayer(0)
    player:GetEffects():AddCollectibleEffect(CollectibleType.COLLECTIBLE_SAD_ONION, true)
    ```
___ 
### Add·Null·Effect () {: aria-label='Functions' }
[ ](#){: .rep .tooltip .badge }
#### void AddNullEffect ( [ItemConfig::NullItemID](../rep/ItemConfig_Item) NullId, boolean AddCostume = true, int Count = 1 ) {: .copyable aria-label='Functions' }

___ 
### Add·Trinket·Effect () {: aria-label='Functions' }
[ ](#){: .rep .tooltip .badge }
#### void AddTrinketEffect ( [TrinketType](../rep/enums/TrinketType) TrinketType, boolean AddCostume = true, int Count = 1 ) {: .copyable aria-label='Functions' }

___ 
### Clear·Effects () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### void ClearEffects ( ) {: .copyable aria-label='Functions' }

___ 
### Get·Collectible·Effect () {: aria-label='Functions' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [TemporaryEffect](../rep/TemporaryEffect) GetCollectibleEffect ( [CollectibleType](../rep/enums/CollectibleType) CollectibleType ) {: .copyable aria-label='Functions' }

___ 
### Get·Collectible·Effect·Num () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### int GetCollectibleEffectNum ( [CollectibleType](../rep/enums/CollectibleType) CollectibleType ) {: .copyable aria-label='Functions' }

___ 
### Get·Effects·List () {: aria-label='Functions' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [EffectList](../rep/CppContainer_Vector_EffectList) GetEffectsList ( ) {: .copyable aria-label='Functions' }

___ 
### Get·Null·Effect () {: aria-label='Functions' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [TemporaryEffect](../rep/TemporaryEffect) GetNullEffect ( [ItemConfig::NullItemID](../rep/ItemConfig_Item) NullId ) {: .copyable aria-label='Functions' }

___ 
### Get·Null·Effect·Num () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### int GetNullEffectNum ( [ItemConfig::NullItemID](../rep/ItemConfig_Item) NullId ) {: .copyable aria-label='Functions' }

___ 
### Get·Trinket·Effect () {: aria-label='Functions' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [TemporaryEffect](../rep/TemporaryEffect) GetTrinketEffect ( [TrinketType](../rep/enums/TrinketType) TrinketType ) {: .copyable aria-label='Functions' }

___ 
### Get·Trinket·Effect·Num () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### int GetTrinketEffectNum ( [TrinketType](../rep/enums/TrinketType) TrinketType ) {: .copyable aria-label='Functions' }

___ 
### Has·Collectible·Effect () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean HasCollectibleEffect ( [CollectibleType](../rep/enums/CollectibleType) CollectibleType ) {: .copyable aria-label='Functions' }

___ 
### Has·Null·Effect () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean HasNullEffect ( [ItemConfig::NullItemID](../rep/ItemConfig_Item) NullId ) {: .copyable aria-label='Functions' }

___ 
### Has·Trinket·Effect () {: aria-label='Functions' }
[ ](#){: .abrep .tooltip .badge }
#### boolean HasTrinketEffect ( [TrinketType](../rep/enums/TrinketType) TrinketType ) {: .copyable aria-label='Functions' }

___ 
### Remove·Collectible·Effect () {: aria-label='Functions' }
[ ](#){: .rep .tooltip .badge }
#### void RemoveCollectibleEffect ( [CollectibleType](../rep/enums/CollectibleType) CollectibleType, int Count = 1 ) {: .copyable aria-label='Functions' }
Count = -1 removes all instances of the effect
___ 
### Remove·Null·Effect () {: aria-label='Functions' }
[ ](#){: .rep .tooltip .badge }
#### void RemoveNullEffect ( [ItemConfig::NullItemID](../rep/ItemConfig_Item) NullId, int Count = 1 ) {: .copyable aria-label='Functions' }
Count = -1 removes all instances of the effect
___ 
### Remove·Trinket·Effect () {: aria-label='Functions' }
[ ](#){: .rep .tooltip .badge }
#### void RemoveTrinketEffect ( [TrinketType](../rep/enums/TrinketType) TrinketType, int Count = 1 ) {: .copyable aria-label='Functions' }
Count = -1 removes all instances of the effect
___ 
