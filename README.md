# VRCLens Mods

VRCLens mods with drag-n-drop VRCFury prefabs

[**Download the latest version**](https://github.com/gummidot/VRCLens-Mods/releases/tag/v1.3.0)

## Requirements

- [VRCFury](https://vrcfury.com/download)

## Installation

Each mod is a VRCFury prefab that you drag-n-drop onto your avatar to install.
You can pick which ones to install, then easily remove them by deleting the prefab.
All mods are local-only or take no extra parameter memory.

1. Import the `VRCLens_Custom` Unity package and find the `Assets/VRCLens_Custom` folder.
1. Drag any of the prefabs onto the `VRCLens` object on your avatar.
   - **Note:** If you re-apply VRCLens, the prefabs will disappear, so you will have to do this again.

![!VRCFury Installation](Doc/VRCFury_Install.png)

> [!WARNING]
> Mods have only been tested with the versions of VRCLens listed below. They could be broken in very old versions, but should work in most recent versions.

## SmoothRotate

**Adds a slider that smooths out camera movement**

Works in both desktop and VR, and can smooth much more than OVR-SmoothTracking.

Last tested: VRCLens 1.9.2

### Usage

The slider will be in your menu under `VRCLens/Custom/SmoothRotate`.
0% is the minimum (default) smoothing, and 100% is the maximum amount of smoothing.

Make sure Stabilize mode is on (the white/yellow hand icon) for this to work.

<video src="https://github.com/user-attachments/assets/05d5c2fd-28e6-4f38-8b98-11be5db84a1b"></video>

### Credits

Thanks to [Minkis](https://www.youtube.com/watch?v=XMcTfFoNUHA) for explaining how to do this.

## DroneSpeed

**Modifies the Drone Speed slider to go slower or faster than default**

There are two versions, only add one to your avatar:

- **Slower** allows the drone to move much slower. 0% is now zero speed.
- **Slower and Faster** allows the drone to move much slower and much faster. 0% is now zero speed, 75% is the original max speed, and 100% is 32x the original max speed.

Last tested: VRCLens 1.9.2

### Usage

Use the built-in Drone Speed slider as usual.

<video src="https://github.com/user-attachments/assets/672eee73-1523-4737-9267-767bda7d8efb"></video>

## FarClipPlane

**Increases the camera's far clipping plane**

In some worlds, far objects disappear in VRCLens because of its short far clip plane of `32000`.
This adds a local-only slider that increases the far clipping plane up to `128000`.

Last tested: VRCLens 1.9.2

### Usage

The slider will be in your menu under `VRCLens/Custom/FarClipPlane`.

<video src="https://github.com/user-attachments/assets/bb43007a-006c-4075-aa23-1c9b4624e407"></video>

Test worlds: [Tulip Riverie․․․](https://vrchat.com/home/world/wrld_fcad2657-05c6-4226-ac5d-9cd1688beb74/info), [Cycle of Life](https://vrchat.com/home/world/wrld_cd085851-4baf-4fb8-9a2a-e0e20f686502/info)

## MaxBlurSize

**Adjusts the maximum blur size for performance**

Adds a local-only slider that lets you adjust the maximum blur size when using DoF, which you can use to improve performance (lower blur size = better performance) or change how the blurring looks.

Last tested: VRCLens 1.9.2

### Usage

The slider will be in your menu under `VRCLens/Custom/MaxBlurSize`.

At 0%, the slider has no effect so it uses whatever blur size you installed VRCLens with. After 0%, the slider increases blur size from `Very Small` up until `Very Large` (see VRCLens installer for the different options).

<video src="https://github.com/user-attachments/assets/d929ee5a-3fec-4bab-8f0e-3e6255932236"></video>
