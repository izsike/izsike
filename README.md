@@ -1,11 +1,11 @@
{
  "_QPVersion": "0.1.1",
  "name": "Gorilla Cosmetics",
  "id": "GorillaCosmetics",
  "author": "RedBrumbler",
  "version": "1.2.7",
  "packageId": "com.AnotherAxiom.GorillaTag",
 - "packageVersion": "1.0.9",
+ + "packageVersion": "1.0.11",
  "description": "Monke be fancy \ud83e\uddd0",
  "coverImage": "cover.png",
  "type": "Cosmetic",
  "dependencies": [
    {
      "id": "monkecodegen",
      "version": ">=0.7.4",
      "downloadIfMissing": "https://github.com/RedBrumbler/MonkeCodegen/releases/download/v0.7.4/MonkeCodegen.qmod"
    },
    {
      "id": "gorillautils",
      "version": ">=0.2.2",
      "downloadIfMissing": "https://github.com/RedBrumbler/GorillaUtils/releases/download/v0.2.2/GorillaUtils.qmod"
    }
  ],
  "modFiles": [
    "libgorillacosmetics.so"
  ],
  "libraryFiles": [
    "libbeatsaber-hook_2_0_3.so",
    "libcustom-types.so",
    "libquest-cosmetic-loader_0_2_1.so",
    "libzip.so"
  ],
  "fileCopies": [
    {
      "name": "HatRack",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/HatRack"
    },
    {
      "name": "Mirror",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Mirror"
    },
    {
      "name": "None",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/None"
    },
    {
      "name": "default",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/default"
    },
    {
      "name": "Amongus.hat",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Hats/Amongus.hat"
    },
    {
      "name": "Crown.hat",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Hats/Crown.hat"
    },
    {
      "name": "Top_Hat.hat",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Hats/Top_Hat.hat"
    },
    {
      "name": "Camo.gmat",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Materials/Camo.gmat"
    },
    {
      "name": "Gold.gmat",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Materials/Gold.gmat"
    },
    {
      "name": "Matrix.gmat",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Materials/Matrix.gmat"
    },
    {
      "name": "Rainbow.gmat",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Materials/Rainbow.gmat"
    },
    {
      "name": "Unity_Default_Material.gmat",
      "destination": "/sdcard/ModData/com.AnotherAxiom.GorillaTag/Mods/GorillaCosmetics/Materials/Unity_Default_Material.gmat"
    }
  ]
}
