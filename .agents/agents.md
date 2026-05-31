# Mivio VR Agents Configuration

## Project Overview
Mivio VR is a premium, high-performance immersive media management and playback application tailored for standalone Virtual Reality headsets like Meta Quest, Pico, and HTC Vive XR. Designed to replicate the ultimate home theater experience, Mivio VR allows users to sit in a virtual cinema and stream media directly from their local network (SMB/WebDAV), without needing a transcoding server.

## Key Technologies
- Engine: Unity 3D (2022.3 LTS or newer)
- Platform: Android (for VR headsets)
- XR Framework: Oculus XR / OpenXR Plugin
- Video Playback: Native Quest player and ExoPlayer for 2D, 3D (SBS/OU), 180°, and 360° videos
- Build Target: Android

## Project Structure
```
mivio-vr/
├── Assets/               # Unity assets (models, textures, scenes, etc.)
├── CONTRIBUTING.md       # Contribution guidelines
├── LICENSE               # License file
├── README.md             # Project documentation
└── SECURITY.md           # Security policy
```

## Development Guidelines
- Target branch for PRs: `beta` (main is production-ready)
- Prerequisites: 
  - Unity 2022.3 LTS (or newer) with Android Build Support
  - Meta Quest Developer Hub (for Quest deployment)
  - Oculus XR / OpenXR Plugin configured in Unity
- Setup process:
  1. Clone repository
  2. Open in Unity Hub
  3. Configure XR settings for target VR platform
  4. Build and run to target device via USB (with Developer Mode enabled)

## Platform Features & Limitations
- ❌ No Local Multi-Account: Accounts and watch states are managed exclusively by the server
- ❌ No Local Playback from Storage: By design, Mivio VR operates only as a streaming client to save headset storage space
- ✅ Home Server Client: Stream media directly from home servers (Plex, Jellyfin, Emby)
- ✅ Immersive Environments: Downloadable GLB/FBX/AssetBundles for virtual cinema rooms and void theaters
- ✅ Internal Marketplace: Community-driven marketplace to upload and download VR environments
- ✅ Native VR Player: Hardware-accelerated decoding using the native Quest player and ExoPlayer for various video formats

## Agent Instructions
When working on this project:
1. Understand Unity's XR architecture and how it integrates with VR headsets
2. Work primarily in the Assets/ directory for VR environments, UI elements, and scripts
3. Ensure compatibility with VR hardware constraints and performance requirements
4. Focus on home server client functionality (Plex, Jellyfin, Emby integration)
5. Optimize for VR performance (maintain high frame rates to prevent motion sickness)
6. Test thoroughly on actual VR headsets with Developer Mode enabled
7. Follow Unity best practices for XR development
8. Pay attention to user comfort and VR-specific design principles
9. Keep security in mind when handling network operations and data parsing
10. Update documentation when changing public APIs or significant functionality