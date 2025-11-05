# 📁 Elite Pentest Framework v6.0 - Folder Setup Instructions

## 🎯 Create This Exact Folder Structure

### Step 1: Create Main Folder
Create this folder on your system:
```
C:\Users\Moiz\Elite_Pentest_Framework_v6\
```

### Step 2: Move All Files to This Folder

Move these files into the folder you just created:

```
📁 C:\Users\Moiz\Elite_Pentest_Framework_v6\
├── 🔥 BeastTm_Enhanced_2025.js              ← Main framework
├── 🛡️ Elite_WAF_Bypass_Config.js            ← WAF bypass config
├── 🧠 Elite_ML_Learning_Config.js           ← ML learning config
├── ⚡ Elite_Pentest_Framework_Loader.js     ← Module loader (NEW)
├── 📋 framework_config.json                 ← User settings (Will be created)
├── 💥 custom_payloads.json                  ← Custom payloads (Will be created)
├── 🎯 target_profiles.json                  ← Target configs (Will be created)
├── 📖 Installation_Usage_Guide.md           ← Detailed guide
├── ⚡ Quick_Setup_Guide.md                  ← Quick setup
└── 📁 Folder_Setup_Instructions.md          ← This file
```

## 🚀 Installation Method: Using the Module Loader

### Option 1: Automatic Module Loading (Recommended)

1. **Install ONLY the module loader** in TamperMonkey:
   - Copy `Elite_Pentest_Framework_Loader.js`
   - Paste into TamperMonkey → Create new script
   - Save

2. **The loader will automatically**:
   - Load all modules from your folder
   - Create default config files
   - Initialize the complete framework
   - Show loading progress

### Option 2: Manual Installation (Basic)

1. **Install main framework** in TamperMonkey:
   - Copy `BeastTm_Enhanced_2025.js`
   - Paste into TamperMonkey → Create new script
   - Save

## 🔧 Configuration Files (Auto-Generated)

When you first run the framework, these config files will be automatically created:

### 📋 framework_config.json
```json
{
  "framework": {
    "PARALLEL_TABS": 8,
    "TEST_DELAY": 800,
    "ENABLE_QUANTUM_BYPASS": true,
    "ENABLE_ML_PREDICTION": true,
    "LOG_LEVEL": "INFO"
  },
  "user_preferences": {
    "theme": "quantum",
    "auto_export": true,
    "notification_level": "important"
  }
}
```

### 💥 custom_payloads.json
```json
{
  "payloads": [
    "<script>console.log(\"custom-payload-1\")</script>",
    "<img src=x onerror=console.log(\"custom-payload-2\")>",
    "javascript:console.log(\"custom-payload-3\")"
  ],
  "categories": {
    "custom": ["basic", "advanced", "experimental"]
  }
}
```

### 🎯 target_profiles.json
```json
{
  "profiles": {
    "testphp.vulnweb.com": {
      "PARALLEL_TABS": 3,
      "TEST_DELAY": 1000,
      "ENABLE_WAF_BYPASS": false
    },
    "portswigger-labs.net": {
      "PARALLEL_TABS": 5,
      "TEST_DELAY": 500,
      "ENABLE_QUANTUM_BYPASS": true
    },
    "localhost": {
      "PARALLEL_TABS": 10,
      "TEST_DELAY": 200,
      "ENABLE_ALL_FEATURES": true
    }
  }
}
```

## 🎛️ How the Module Loader Works

### Features:
- ✅ **Automatic file loading** from your local folder
- ✅ **Error handling** with retry mechanisms
- ✅ **Configuration management** with defaults
- ✅ **Progress indicators** during loading
- ✅ **Target-specific profiles** for different sites
- ✅ **Custom payload integration**

### Loading Process:
1. **Loads main framework** (`BeastTm_Enhanced_2025.js`)
2. **Loads config modules** (WAF bypass, ML config)
3. **Applies user configurations** from JSON files
4. **Initializes complete system**
5. **Shows load summary**

## 🔧 Customization Examples

### Change Framework Settings:
Edit `framework_config.json`:
```json
{
  "framework": {
    "PARALLEL_TABS": 12,           // More parallel testing
    "TEST_DELAY": 500,             // Faster testing
    "ENABLE_QUANTUM_BYPASS": true, // Enable advanced bypasses
    "MAX_TESTS_PER_PARAM": 1000    // More thorough testing
  }
}
```

### Add Custom Payloads:
Edit `custom_payloads.json`:
```json
{
  "payloads": [
    "<script>alert('XSS by Moiz')</script>",
    "<img src=x onerror=fetch('https://your-webhook.com/xss')>",
    "javascript:document.location='https://evil.com'"
  ]
}
```

### Target-Specific Settings:
Edit `target_profiles.json`:
```json
{
  "profiles": {
    "my-target-app.com": {
      "PARALLEL_TABS": 2,              // Gentle testing
      "TEST_DELAY": 2000,              // Slow and careful
      "ENABLE_WAF_BYPASS": true,       // Bypass WAF
      "CUSTOM_PAYLOADS_ONLY": true     // Use only custom payloads
    }
  }
}
```

## 🚨 Security Notes

### ⚠️ File Access Requirements:
- TamperMonkey needs `file://` access to load local files
- This is automatically granted for userscripts
- Files must be in the exact path specified

### 🔒 Safe Practices:
- Keep framework files in a dedicated folder
- Don't share config files (may contain sensitive data)
- Regular backup of custom configurations
- Review generated config files before use

## 🐛 Troubleshooting

### File Loading Issues:
```
❌ Error: "Failed to load main framework"
✅ Solution: Check file path and ensure files are in correct folder
```

### Permission Issues:
```
❌ Error: "Network error loading file"
✅ Solution: Ensure TamperMonkey has file access permissions
```

### Config Loading Issues:
```
❌ Error: "Config file not found"
✅ Solution: Let the framework create default configs first
```

## 🎯 Quick Start Commands

### Create the folder:
```bash
mkdir "C:\Users\Moiz\Elite_Pentest_Framework_v6"
```

### Copy files to folder:
```bash
# Copy all .js and .md files to the folder
```

### Install in TamperMonkey:
```javascript
// Copy Elite_Pentest_Framework_Loader.js into TamperMonkey
```

## 🎊 You're Ready!

After setup, you'll have:
- ✅ **Modular framework** with automatic loading
- ✅ **Custom configurations** for different targets  
- ✅ **Advanced features** from separate modules
- ✅ **Easy customization** through JSON files
- ✅ **Professional setup** for elite-level testing

Navigate to any target site and watch the magic happen! 🚀