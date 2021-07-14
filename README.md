# OpenAL Soft

**OpenAL Soft** is an LGPL-licensed, cross-platform, software implementation of the OpenAL 3D audio API.

OpenAL provides capabilities for playing audio in a virtual 3D environment. Distance attenuation, doppler shift, and directional sound emitters are among the features handled by the API. More advanced effects, including air absorption, occlusion, and environmental reverb, are available through the EFX extension. It also facilitates streaming audio, multi-channel buffers, and audio capture.

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/openal-soft
$ dnf install -y openal-soft
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y openal-soft
```

## Remove

```
$ dnf erase -y openal-soft
$ dnf copr remove pkgstore/openal-soft
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/openal-soft).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/openal-soft) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
