# Jellyfin Plugin Repository

This repository hosts the manifest for Jellyfin plugins.

## Overview
The Enhancer Plugin for Jellyfin enhances video and audio quality with upscaling options and AI-based algorithms. It allows users to configure various settings to improve their media experience.

## Features
- Video enhancement using FFmpeg or Dolby algorithms
- Audio enhancement with options for Dolby Atmos and AAC formats
- AI-based upscaling with Basic and Advanced models
- Customizable video resolutions, bitrates, and encoding quality
- Generates detailed NFO files for enhanced media

## Installation
1. **Dependencies**: The plugin requires FFmpeg, Python, and TensorFlow. The installation script will handle these dependencies.
2. **Clone the repository**: 
    ```bash
    git clone https://github.com/YourGitHubUsername/EnhancerPlugin.git
    ```
3. **Run the installation script**:
    ```bash
    cd EnhancerPlugin
    ./install.sh
    ```
4. **Build the plugin**: 
    Open the project `Jellyfin.Plugin.Enhancer.sln` in your preferred IDE (e.g., Visual Studio) and build the project to generate the necessary DLL files.
5. **Deploy the plugin**: 
    Copy the generated DLL files to the Jellyfin plugins directory (default is `~/.config/jellyfin/plugins`).
6. **Restart Jellyfin**: 
    Restart the Jellyfin server to load the new plugin.

## How to Add This Repository to Jellyfin

1. Go to the Jellyfin dashboard.
2. Navigate to the "Plugins" section.
3. Click on "Repositories".
4. Add a new repository with the following URL: