# yuna0x0's VPM Package Listing

![GitHub deployments](https://img.shields.io/github/actions/workflow/status/yuna0x0/vpm-listing/build-listing.yml?label=Build%20Package%20Listing)

- Website: https://vpm.yuna0x0.com
- Listing URL: `https://vpm.yuna0x0.com/index.json`

## Adding the listing

With [ALCOM](https://vrc-get.anatawa12.com/en/alcom/), an open-source package manager for Unity
projects: open **Packages**, choose **Add Repository**, and enter the listing URL.

From a terminal with [vrc-get](https://github.com/vrc-get/vrc-get), which ALCOM is built on:

```shell
vrc-get repo add https://vpm.yuna0x0.com/index.json
vrc-get install <package name>
```

Or with VRChat's [VPM CLI](https://vcc.docs.vrchat.com/vpm/cli/):

```shell
vpm add repo https://vpm.yuna0x0.com/index.json
vpm add package <package name>
```

## Packages

| Package | Description |
|---|---|
| [Watari](https://github.com/yuna0x0/watari-basis) | Converter for [Basis](https://basisvr.org/): VRChat, VRM and Dynamic Bone components become jiggle physics, constraints, the avatar descriptor, HVR Vixxy controls and authored motion. |
