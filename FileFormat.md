# Useful links #

  * http://www.minecraftwiki.net/wiki/Chunk_format
  * http://www.minecraftwiki.net/wiki/Alpha_Level_Format
  * http://www.minecraftwiki.net/wiki/Region_file_format
  * http://www.minecraftwiki.net/wiki/Anvil_file_format

# Typical level.dat (1.2.3) #
```
TAG_Compound(""): count=1
  TAG_Compound("Data"): count=18
    TAG_Byte("thundering"): dec=0
    TAG_Long("LastPlayed"): val=1328889918931
    TAG_Compound("Player"): count=27
      TAG_List("Motion"): count=3 type=6
        TAG_Double(""): val=4.183952625806089E-9
        TAG_Double(""): val=-0.0784000015258789
        TAG_Double(""): val=7.77779081048445E-9
      ENDOF TAG_List("Motion")
      TAG_Float("foodExhaustionLevel"): val=1.5497185
      TAG_Int("foodTickTimer"): val=0
      TAG_Int("XpLevel"): val=1
      TAG_Short("Health"): val=20
      TAG_List("Inventory"): count=3 type=10
        TAG_Compound(""): count=4
          TAG_Short("id"): val=274
          TAG_Short("Damage"): val=78
          TAG_Byte("Count"): dec=1
          TAG_Byte("Slot"): dec=0
        ENDOF TAG_Compound("")
        TAG_Compound(""): count=4
          TAG_Short("id"): val=364
          TAG_Short("Damage"): val=0
          TAG_Byte("Count"): dec=3
          TAG_Byte("Slot"): dec=7
        ENDOF TAG_Compound("")
        TAG_Compound(""): count=4
          TAG_Short("id"): val=50
          TAG_Short("Damage"): val=0
          TAG_Byte("Count"): dec=59
          TAG_Byte("Slot"): dec=8
        ENDOF TAG_Compound("")
      ENDOF TAG_List("Inventory")
      TAG_Short("AttackTime"): val=0
      TAG_Byte("Sleeping"): dec=0
      TAG_Int("SpawnX"): val=222
      TAG_Short("Fire"): val=-20
      TAG_Int("SpawnY"): val=56
      TAG_Int("SpawnZ"): val=250
      TAG_Int("foodLevel"): val=18
      TAG_Int("Score"): val=9
      TAG_Short("DeathTime"): val=0
      TAG_Float("XpP"): val=0.2
      TAG_Short("SleepTimer"): val=0
      TAG_Short("HurtTime"): val=0
      TAG_Byte("OnGround"): dec=1
      TAG_Int("Dimension"): val=0
      TAG_Short("Air"): val=300
      TAG_List("Pos"): count=3 type=6
        TAG_Double(""): val=220.73184779290204
        TAG_Double(""): val=57.62000000476837
        TAG_Double(""): val=248.80455604498616
      ENDOF TAG_List("Pos")
      TAG_Float("foodSaturationLevel"): val=14.0
      TAG_Compound("abilities"): count=4
        TAG_Byte("flying"): dec=0
        TAG_Byte("instabuild"): dec=0
        TAG_Byte("mayfly"): dec=0
        TAG_Byte("invulnerable"): dec=0
      ENDOF TAG_Compound("abilities")
      TAG_Float("FallDistance"): val=0.0
      TAG_Int("XpTotal"): val=9
      TAG_List("Rotation"): count=2 type=5
        TAG_Float(""): val=871.5092
        TAG_Float(""): val=28.650015
      ENDOF TAG_List("Rotation")
    ENDOF TAG_Compound("Player")
    TAG_Long("RandomSeed"): val=3940377918645349980
    TAG_Int("GameType"): val=0
    TAG_Byte("MapFeatures"): dec=1
    TAG_Int("version"): val=19132
    TAG_Long("Time"): val=48204
    TAG_Byte("raining"): dec=0
    TAG_Int("thunderTime"): val=38399
    TAG_Int("SpawnX"): val=180
    TAG_Byte("hardcore"): dec=0
    TAG_Int("SpawnY"): val=64
    TAG_Int("SpawnZ"): val=256
    TAG_String("LevelName"): val=1.1
    TAG_String("generatorName"): val=DEFAULT
    TAG_Long("SizeOnDisk"): val=0
    TAG_Int("rainTime"): val=103672
  ENDOF TAG_Compound("Data")
ENDOF TAG_Compound("")
```

# Typical Anvil content #
```
TAG_Compound(""): count=1
  TAG_Compound("Level"): count=9
    TAG_List("Entities"): count=0 type=1
    ENDOF TAG_List("Entities")
    TAG_ByteArray("Biomes"): size=256
    TAG_Long("LastUpdate"): val=4317
    TAG_Int("xPos"): val=119
    TAG_Int("zPos"): val=55
    TAG_List("TileEntities"): count=0 type=1
    ENDOF TAG_List("TileEntities")
    TAG_Byte("TerrainPopulated"): dec=1
    TAG_IntArray("HeightMap"): size=256
    TAG_List("Sections"): count=1 type=10
      TAG_Compound(""): count=5
        TAG_ByteArray("Data"): size=2048
        TAG_ByteArray("SkyLight"): size=2048
        TAG_ByteArray("BlockLight"): size=2048
        TAG_Byte("Y"): dec=0
        TAG_ByteArray("Blocks"): size=4096
      ENDOF TAG_Compound("")
    ENDOF TAG_List("Sections")
  ENDOF TAG_Compound("Level")
ENDOF TAG_Compound("")
```

# Typical MC Region content #
```
TAG_Compound(""): count=1
  TAG_Compound("Level"): count=11
    TAG_ByteArray("Data"): size=16384
    TAG_List("Entities"): count=0 type=1
    ENDOF TAG_List("Entities")
    TAG_Long("LastUpdate"): val=217439
    TAG_Int("xPos"): val=38
    TAG_Int("zPos"): val=35
    TAG_List("TileEntities"): count=0 type=1
    ENDOF TAG_List("TileEntities")
    TAG_Byte("TerrainPopulated"): dec=1
    TAG_ByteArray("SkyLight"): size=16384
    TAG_ByteArray("HeightMap"): size=256
    TAG_ByteArray("BlockLight"): size=16384
    TAG_ByteArray("Blocks"): size=32768
  ENDOF TAG_Compound("Level")
ENDOF TAG_Compound("")
```