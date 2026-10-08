# Mekanism Tools - Unofficial Fan Build (26.1.2)

Adds Mekanism material-based tools, weapons and armor. This is the matching Tools module from the fan-maintained ATM11 compatibility build.

## Unofficial fan build and credits

This adaptation was prepared by **victor0hxz** for the ATM11 compatibility project. It is an **unofficial version made by fans**, not an official release. It is not affiliated with or endorsed by the original authors or the All the Mods team.

Original authors: **Aidan C. Brady and the Mekanism contributors**. [Original source project](https://github.com/mekanism/Mekanism). The original MIT license and copyright notices are preserved. The original mod authors retain credit for the mod and its content.

## Requirements and installation

Minecraft **26.1.2**, NeoForge and **Java 25**. Requires matching Mekanism 10.8.0 for Minecraft 26.1.2.

Replace the older copy of the same mod; do not install the official build and this build together because the mod ID is unchanged. Keep Mekanism modules on matching versions. This older source build is a separate alternative to the Version Locked modules used by the newer Extras tests; mixing them has not been validated. Dependencies are not bundled.

## Validation and release status

Compiled artifact located in the previous ATM11 server correction package. Archive integrity and metadata verified; no new full-pack runtime validation was performed for this publication.

This initial file should be submitted as **Beta**, pending full-pack community gameplay tests. Do not interpret a compiled JAR as a guarantee that every gameplay scenario has been tested.

## Downloads and support

Download the unofficial prerelease JAR from [this repository's releases](https://github.com/victor0hxz/MekanismTools-Unofficial-ATM11/releases). Report problems to [this port's issue tracker](https://github.com/victor0hxz/MekanismTools-Unofficial-ATM11/issues). Do not direct port-specific support requests to the original authors.

## Build source

This repository preserves the local production source snapshot used by the compatibility project, including the original license. Install Java 25 and use the Gradle wrapper. Torchmaster: `gradlew.bat :neoforge:jar`; Mekanism and modules: `gradlew.bat jar`; SFM: run `gradlew.bat build` inside `platform/minecraft`. Original optional dependency versions remain in the inherited Gradle configuration. An uncached rebuild of this snapshot has not been validated in this publication step.

The core and all companion modules share the original Mekanism source tree. Each module has its own repository and release; this repository distributes only its named module JAR. Do not mix this older source build with Version Locked modules without testing.
