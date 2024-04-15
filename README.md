# NewLBLTC0re - LinearPaper that uses more bug fixes and modules. 
Minecraft Version 1.19.4.
Linear region file format uses about half of the original Anvil region file without any loss of data.

Check [this repository for documentation and tools](https://github.com/xymb-endcrystalme/LinearRegionFileFormatTools).



This fork is 100% compatible with Paper, it just reads and saves region files in `.linear` instead of `.mca`.

Great for giant (TB+) worlds. Offers no advantages for tiny worlds, it's just a region file format.

## Compiling

```
./gradlew applyPatches
./gradlew createReobfPaperclipJar
```

Your compiled .jar will be in `build/libs/`.

Forked From LinearPaper(https://github.com/xymb-endcrystalme/LinearPaper)

准备抄袭名单：
Purpur
https://github.com/PurpurMC/Purpur/tree/ver/1.19.4
