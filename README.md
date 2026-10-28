# esw1234.github.io

GitHub Pages repository for Enhanced Chat (Embedded Service for Web) test pages and automation tools.

## 📚 Documentation & Tools

### Enhanced Chat Deployment Automation
- **[Testing Guide](https://tiffanytso-sfdc.github.io/esw1234.github.io/scripts/ec-deployment-creation/enhanced-chat-testing-guide.html)** - Comprehensive guide with all 11 fixes, detailed test cases, and beta testing checklist
- **[Setup Demo](https://tiffanytso-sfdc.github.io/esw1234.github.io/scripts/ec-deployment-creation/enhanced-chat-setup-demo.html)** - Visual overview of the automated setup process

### Automation Package
Download the complete package: [enhanced-chat-setup-package.zip](https://drive.google.com/file/d/10w6yZPIdcWvIWLay9jMnhqvWdRAwbhoa/view?usp=sharing)

**Contents:**
- `setup-enhanced-chat-complete-auto.sh` - Main automation script
- `republish-enhanced-chat.sh` - Helper for republishing deployments
- `ENHANCED_CHAT_SETUP_GUIDE.md` - User guide with step-by-step instructions

**Quick Start:**
```bash
./setup-enhanced-chat-complete-auto.sh
```

## 📁 Repository Structure

```
esw1234.github.io/
├── scripts/
│   └── ec-deployment-creation/          # Enhanced Chat deployment tools
│       ├── enhanced-chat-testing-guide.html
│       └── enhanced-chat-setup-demo.html
├── images/                              # Shared image assets
│   ├── SFDCLogo.png
│   ├── SFDCTower.png
│   ├── Ursa_Major_Logo_2.png
│   └── avatar-logo-streaming.png
├── CWC/                                 # Chat Window Configuration test pages
│   └── SDB3/                           # CWC01-CWC15 test pages
├── 254/ through 266/                    # Active test directories (release versions)
└── esw1234.github.io-legacy/            # Historical test files (preserved)
```

## 🧪 Active Test Directories

Test pages organized by release version:
- `CWC/` - Chat Window Configuration test pages (CWC01-CWC15)
- `254/` - Release 254 test pages
- `256/` - Release 256 test pages
- `258/` - Release 258 test pages
- `260/` - Release 260 test pages
- `262/` - Release 262 test pages
- `264/` - Release 264 test pages
- `266/` - Release 266 test pages

## 📦 Legacy Content

The `esw1234.github.io-legacy/` directory contains historical test files from previous development cycles. These are preserved for reference but are not actively maintained.

## 🚀 Using This Repo

### For Testing Enhanced Chat
1. Visit the [Testing Guide](https://tiffanytso-sfdc.github.io/esw1234.github.io/scripts/ec-deployment-creation/enhanced-chat-testing-guide.html)
2. Download the automation package
3. Follow the quick start instructions

### For Adding Test Pages
Test pages should be organized by release version in the appropriate numbered directory (e.g., `266/` for release 266).

### GitHub Pages URLs
All HTML files in this repo are automatically published via GitHub Pages:
```
https://tiffanytso-sfdc.github.io/esw1234.github.io/<path-to-file>.html
```

## 🔧 What's New (v2.1)

The Enhanced Chat deployment automation script now includes:
- ✅ **11 fixes** including 2 critical bugs
- ✅ **Auto-channel detection** - works with any orgfarm
- ✅ **Non-interactive mode** - CI/CD ready
- ✅ **3-tier git fallback** - works without SSH keys
- ✅ **Comprehensive error handling** - clear messages and recovery steps

### Critical Fixes
- **Fix #8**: Wrong site selection (queries by deployment relationship)
- **Fix #9**: SCRT2 URL mismatch (works across all orgfarm types)

## 📊 Stats

- **Time saved**: ~20 minutes → ~1 minute per deployment
- **Automation coverage**: 95% reduction in manual steps
- **Support**: All orgfarm types (pc-rnd, test1, test2, etc.)

## 🆘 Support

For issues or questions:
- Review the [Testing Guide](https://tiffanytso-sfdc.github.io/esw1234.github.io/scripts/ec-deployment-creation/enhanced-chat-testing-guide.html)
- Check the troubleshooting section in `ENHANCED_CHAT_SETUP_GUIDE.md`
- Reach out to the team via the announcement thread

## 📝 Contributing

When adding new test pages:
1. Place them in the appropriate release directory
2. Use descriptive filenames (e.g., `feature-test-deployment.html`)
3. Include comments documenting the test purpose
4. Commit with clear messages describing what's being tested

---

**Last Updated**: October 28, 2026  
**Version**: 2.1  
**Maintainer**: Tiffany Tso
