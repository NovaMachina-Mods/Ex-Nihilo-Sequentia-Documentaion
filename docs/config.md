# Configuration File
Below is a detailed description of what a value does in the configuration file.

!!! Important
    A tick is 1/20 of a second.<br>
    A bucket holds 1000 millibuckets.


## Infested Leaves
`secondsToTransformLeaves`
: Number of seconds to for leaves to become completely infested.<br>Default: 10<br>Range: > 1

`ticksBetweenSpreadAttempt`
: Number of ticks between infested leave spread attempts.<br>Default: 100<br>Range: > 1
	
`spreadChance`
: Percentage of the time that infested leaves will spread.<br>Default: 0.3<br>Range: 0.001 ~ 1.0

## Barrel
`barrelNumberOfBuckets`
: Number of buckets the barrel will hold.<br>Default: 1<br>Range: > 1

`woodBarrelMaxTemp`
: The max temperature a barrel can accept; water is 300 <br>Default: 300<br>Range: > 0

`showParticles`
: Should the barrel create particles?<br>Default: true

`rainFillAmount`
: How much fluid rain will fill per iteration.<br>Default: 2<br>Range: > 1

### Mob Spawn
`secondsToSpawnMobs`
: Number of seconds to spawn mobs.<br>Default: 10<br>Range: > 1

### Compost
`secondsToCompost`
: Number of seconds to compost.<br>Default: 10<br>Range: > 1

`maxSolidAmount`
: How much solids need to be in barrel before composting starts.<br>Default: 1000<br>Range: > 1

### Fluid Transform
`secondsToTransformFluid`
: Number of seconds to transform fluids.<br>Default: 10<br>Range: > 1

## Pebble
`pebbleDamage`
: How much half hearts damage a pebble should do.<br>Default: 0<br>Range: > 0

## Ore
`enableOreOverride`
: Allows ores to be enabled or disabled by this config file.<br>Default: false

`enablePlatinum`
: Enable platinum ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableUranium`
: Enable uranium ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableGold`
: Enable gold ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableSilver`
: Enable silver ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableCopper`
: Enable copper ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableNickel`
: Enable nickel ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableIron`
: Enable iron ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableAluminum`
: Enable aluminum ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableLead`
: Enable lead ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableZinc`
: Enable zinc ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

`enableTin`
: Enable tin ore pieces, chunks and ingots if they exist. `enableOreOverride` must be true for this to work.<br>Default: true

## Debug
`enableDebugLogging`
: Enable extra logging?<br>Default: false

## Crook
`maxBonusStringCount`
: Maximum additional string that a crook will drop from infested leaves in addition to the minimum string count.<br>Default: 3<br>Range: > 0

`minStringCount`
: Minimum string that a crook will drop from infested leaves.<br>Default: 2<br>Range: > 1

`vanillaDropSimulateCount`
: Number of times the crook will "break" a leaf block to get drops.<br>Default: 3<br>Range: > 1

## Durability
### Hammers
`hammerWoodValue`
: Durability of Wooden Hammer<br>Default: 128<br>Range: > 1

`hammerStoneValue`
: Durability of Stone Hammer<br>Default: 256<br>Range: > 1

`hammerNetheriteValue`
: Durability of Netherite Hammer<br>Default: 8192<br>Range: > 1

`hammerIronValue`
: Durability of Iron Hammer<br>Default: 512<br>Range: > 1

`hammerDiamondValue`
: Durability of Diamond Hammer<br>Default: 4096<br>Range: > 1

`hammerGoldValue`
: Durability of Gold Hammer<br>Default: 64<br>Range: > 1

### Crooks
`crookDiamondValue`
: Durability of Diamond Crook<br>Default: 2048<br>Range: > 1

`crookIronValue`
: Durability of Iron Crook<br>Default: 256<br>Range: > 1

`crookBoneValue`
: Durability of Bone Crook<br>Default: 256<br>Range: > 1

`crookStoneValue`
: Durability of Stone Crook<br>Default: 256<br>Range: > 1

`crookGoldValue`
: Durability of Gold Crook<br>Default: 32<br>Range: > 1

`crookGraniteValue`
: Durability of Granite Crook<br>Default: 256<br>Range: > 1

`crookAndesiteValue`
: Durability of Andesite Crook<br>Default: 256<br>Range: > 1

`crookDioriteValue`
: Durability of Diorite Crook<br>Default: 256<br>Range: > 1

`crookWoodValue`
: Durability of Wooden Crook<br>Default: 128<br>Range: > 1

### Meshes
`meshNetheriteValue`
: Durability of Netherite Mesh (Only useful if enableMeshDurability is true)<br>Default: 2031<br>Range: > 1

`meshDiamondValue`
: Durability of Diamond Mesh (Only useful if enableMeshDurability is true)<br>Default: 1561<br>Range: > 1

`meshIronValue`
: Durability of Iron Mesh (Only useful if enableMeshDurability is true)<br>Default: 250<br>Range: > 1

`meshStringValue`
: Durability of String Mesh (Only useful if enableMeshDurability is true)<br>Default: 59<br>Range: > 1

`meshEmeraldValue`
: Durability of Emerald Mesh (Only useful if enableMeshDurability is true)<br>Default: 1561<br>Range: > 1

`meshFlintValue`
: Durability of Flint Mesh (Only useful if enableMeshDurability is true)<br>Default: 131<br>Range: > 1

## Crucible
`ticksBetweenMelts`
: Ticks between melting operations<br>Default: 20<br>Range: > 1

`crucibleNumberOfBuckets`
: Number of buckets the crucible will hold<br>Default: 4<br>Range: > 1

### Wooden Crucible
`woodHeatRate`
: Heat rate the Wood Crucible will use regardless of heat source below<br>Default: 2<br>Range: > 1

## Sieve
`flattenSieveRecipes`
: Sieve will get results for all mesh tiers below the one in the sieve<br>Default: true

`maxSieveClicks`
: The number of sieve clicks required to sieve a block.<br>Default: 10<br>Range: 1 ~ 10

`enableMeshDurability`
: Meshes will have durability and can break, but don't stack.<br>Default: false

`meshStackSize`
: Meshes will stack, but don't have durability.<br>Default: 64<br>Range: 1 ~ 64

`sieveRange`
: Defines the radius that a sieve will attempt to activate other sieves<br>Default: 2<br>Range: 0 ~ 5