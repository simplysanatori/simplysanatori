# Hi, I'm Sana

Android developer and Steam Frame enthusiast. Most of my work is on Arm: Kotlin and Java over the NDK, JNI, Vulkan and OpenXR, and lately a lot of native Linux arm64.

I spend my spare time porting things to Valve's Steam Frame, whatever catches my fancy: VR games, streaming clients, the odd tool. The newer ports are plain Linux arm64 programs running in the Frame's own SteamVR, with no Lepton, APK or PC involved.

## Projects

- [GalaxyFrame](https://github.com/simplysanatori/GalaxyFrame): Super Mario Galaxy in VR, natively on the Frame. A Linux arm64 build of GalaxyQuest (Petari decompilation) with its own Vulkan renderer, both eyes rendered every refresh of the 120 Hz display. Bring your own disc.
- [PrimedFrame](https://github.com/simplysanatori/PrimedFrame): Metroid Prime in VR, natively on the Frame. A Linux arm64 build of PrimedGun (Dolphin based) with frame pacing tuned for SteamVR, holding 60 game frames a second on the 120 Hz display. Bring your own disc.
- [Moonlight XR for Frame](https://github.com/simplysanatori/moonlight-xr-steam-frame): a native game streaming client for the Frame, written in C on OpenXR and Vulkan. Hardware H.264 and HEVC decode, flat or curved screen, passthrough and rooms, 2D-to-3D, Frame controllers as mouse or gamepad, streaming over Wi-Fi or the Steam Frame Wireless Adapter.
- [KartFrame](https://github.com/simplysanatori/KartFrame): Mario Kart Wii VR (Wiicompiled VR PLUS) running standalone on the Frame through Lepton at 90 Hz, with a patched kit, a Frame controller layout and an installer.

[moonlight-xr-lepton](https://github.com/simplysanatori/moonlight-xr-lepton) is the earlier Android build of Moonlight XR for the Frame through Lepton, superseded by the native client above.

## How I work

These ports are AI-assisted. I lean on LLM coding tools for a lot of the code, which is how one person turns a port around in days rather than months; I pick the targets, direct the work, test on the headset and own the results. Each repo says so in its README.

## Support

If you would like more Steam Frame ports, you can [buy me a coffee](https://ko-fi.com/sana748653). It pays for the Claude API credits these ports are built with, spent as carefully as I can. Where a port has an upstream with its own donation link, support them first; each repo's README says who.
