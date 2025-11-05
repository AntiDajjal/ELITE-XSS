# ⚡ Quick Setup Guide - Elite Pentest Framework v6.0

## 🚀 Fastest Way to Get Started (2 Minutes)

### Step 1: Install in TamperMonkey

1. **Open TamperMonkey** → Dashboard → Create new script
2. **Copy & paste** the entire `BeastTm_Enhanced_2025.js` file
3. **Save** (Ctrl+S)

### Step 2: Add Your Target Domains

**BEFORE TESTING** - Edit this line in the script:

```javascript
WHITELIST_DOMAINS: [
  'testphp.vulnweb.com',      // ✅ Safe test site
  'demo.testfire.net',        // ✅ IBM test app
  'portswigger-labs.net',     // ✅ PortSwigger labs
  'YOUR-DOMAIN.com',          // ⚠️ ADD YOUR AUTHORIZED DOMAIN HERE
  'localhost'                 // ✅ Local testing
],
```

### Step 3: Navigate & Test

1. **Go to target site** with URL parameters:
   ```
   https://testphp.vulnweb.com/search.php?test=hello&id=123
   ```

2. **Dashboard appears** in top-right corner automatically

3. **Click "🚀 START TESTING"** button

4. **Watch the magic happen!** 🎯

## 🎛️ What You'll See

- **Elite Dashboard** with quantum effects
- **Real-time stats**: Tests, hits, success rate
- **ML insights**: Learning progress
- **WAF detection**: If any security is detected
- **Progress bar**: Testing completion
- **Auto-reports**: Downloaded when complete

## 📁 File Structure Overview

You have these files:
```
📁 Elite Pentest Framework v6.0/
├── 🔥 BeastTm_Enhanced_2025.js           ← MAIN FILE (Install this)
├── 🛡️ Elite_WAF_Bypass_Config.js         ← WAF bypass settings
├── 🧠 Elite_ML_Learning_Config.js        ← ML configuration  
├── 📖 Installation_Usage_Guide.md        ← Detailed guide
└── ⚡ Quick_Setup_Guide.md               ← This file
```

## 🎯 Three Usage Options

### Option 1: Basic User (Easiest)
- Just install `BeastTm_Enhanced_2025.js` in TamperMonkey
- Everything works out of the box
- All advanced features included

### Option 2: Advanced User
- Install main file + configuration modules
- Get additional UI panels for fine-tuning
- More control over ML and WAF settings

### Option 3: Expert User
- Modify configurations directly in code
- Add custom payloads and techniques
- Integrate with external security tools

## 🚨 Legal & Safety Reminders

⚠️ **CRITICAL**: Only test sites you own or have permission to test!

✅ **Safe test sites**:
- testphp.vulnweb.com
- demo.testfire.net  
- portswigger-labs.net
- Your own applications

❌ **Never test**:
- Production sites without permission
- Third-party applications
- Government or military sites
- Banking/financial sites

## 🔧 Quick Troubleshooting

**Dashboard not showing?**
- Check TamperMonkey is enabled for the site
- Refresh the page
- Check browser console for errors

**"Domain not authorized" error?**
- Add your domain to WHITELIST_DOMAINS array
- Save the script and refresh

**No parameters detected?**
- Ensure URL has parameters: `?param=value`
- Try: `?test=hello&search=world`

**Slow performance?**
- Reduce PARALLEL_TABS from 8 to 3
- Increase TEST_DELAY from 800 to 2000

## 🎊 Test Site Recommendations

### Beginner Friendly:
```
https://testphp.vulnweb.com/search.php?test=hello
https://demo.testfire.net/bank/main.jsp?content=personal_deposit
```

### Intermediate:
```
https://portswigger-labs.net/xss/reflected?search=test
```

### Advanced (Your Own Apps):
```
https://your-app.com/search?q=test&filter=all
https://your-api.com/v1/users?search=admin
```

## 📊 Understanding Results

**Green numbers** = Good (vulnerabilities found)
**Yellow numbers** = In progress
**Red numbers** = Errors/issues

**Success indicators**:
- 🎯 "XSS Hit found!" in console
- Dashboard shows hits > 0
- Automatic report download

## 🎓 Pro Tips

1. **Start with safe test sites** to learn the interface
2. **Monitor the console** for detailed information  
3. **Use quantum mode** for advanced WAF bypass
4. **Export reports** for documentation
5. **Let ML learn** - it gets better with use!

---

## 🚀 Ready to Go?

1. Install the main script in TamperMonkey
2. Add your domains to whitelist
3. Navigate to target with URL parameters
4. Click START TESTING
5. Watch the elite-level automation work!

**Happy ethical hacking!** 🎯🔓