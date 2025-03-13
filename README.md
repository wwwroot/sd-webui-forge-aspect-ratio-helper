# Aspect Ratio Helper for SD WebUI & Forge [![pytest](https://github.com/wwwroot/sd-webui-forge-aspect-ratio-helper/actions/workflows/pytest.yml/badge.svg?branch=main)](https://github.com/wwwroot/sd-webui-forge-aspect-ratio-helper/actions/workflows/pytest.yml)

**Maintained fork** of the original Aspect Ratio Helper extension, now compatible with both [AUTOMATIC1111 WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) and [SD WebUI Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge).

![user-interface.png](docs%2Fui.png)

## 🚀 Features & Updates
- Full compatibility with Gradio 4.40.0+
- Working with both SD WebUI and SD WebUI Forge
- Fixed dimension scaling operations
- Updated component handling for modern WebUI versions
- Retains all original functionality with improved stability

## 📥 Installation
1. In WebUI/Forge, go to **Extensions** tab
2. Select **Install from URL**
3. Paste URL: `https://github.com/wwwroot/sd-webui-forge-aspect-ratio-helper`
4. Click Install
5. Reload UI

## ✨ Key Features
**Aspect Ratio Controls**
- Configurable aspect ratio presets with auto-scaling
- Lock/Image/Swap functionality
- Interactive dimension locking

**Smart Scaling Tools**
- Scale to maximum/minimum dimensions
- Percentage-based scaling (-25% to +200%)
- Preset aspect ratio buttons (1:1, 16:9, 9:16, etc.)
- Real-time dimension clamping

**Enhanced Compatibility**
- Works seamlessly with ControlNet and other extensions
- Optimized for modern WebUI versions
- Regular maintenance and updates

## ⚙️ Settings
Customize through **Settings → Aspect Ratio Helper**:
- Accordion behavior
- UI component order
- Preset aspect ratios (editable list)
- Percentage scaling options
- Dimension limits (64-2048)
- Display formats

![settings.png](docs%2Fopts.png)

## 🛠️ For Users of Original Version
This fork maintains all original functionality while adding:
- Critical bug fixes for modern WebUI versions
- Gradio 4.x compatibility
- Improved error handling
- Future-proofed codebase

## 🤝 Contributing
Contributions welcome! Please:
1. Open issues in [GitHub repository](https://github.com/wwwroot/sd-webui-forge-aspect-ratio-helper)
2. Follow existing code style
3. Test changes thoroughly
4. Submit PR against `main` branch

## 📚 Development
```bash
# Install dependencies
pip install pytest

# Run tests
pytest
```

## 📜 License
MIT License - Maintained by [@wwwroot](https://github.com/wwwroot)

---

**Note**: This extension is community-maintained. For issues specific to SD WebUI Forge, please ensure you're using the latest version of both Forge and this extension.

```diff
- Original repository archived - 
+ Actively maintained fork with modern compatibility +
```