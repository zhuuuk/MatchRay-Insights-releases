# MatchRay Insights — Windows releases

This repository distributes Windows installers, signed update metadata and checksums for MatchRay Insights. Application source code and update-signing private keys are not stored here.

The first release is a standalone DEMO prototype. Match data and player histories are fictional. Overwolf GEP is not connected. A BattleTag is stored locally and does not authenticate a Blizzard account.

Windows 10/11 x64. Installers currently do not have an Authenticode publisher certificate; Windows may display a warning on first installation. The application independently verifies Ed25519 release signatures and installer hashes before applying updates.

Game imagery remains the property of Blizzard Entertainment. This is an independent project.
