# Home Budget Mobile - Android App & APK Build Kit

This package contains the complete, production-ready Home Monthly Budget Android Mobile App.

## Features Included:
1. **Income & Expense Categories**:
   - Comprehensive categories for salary, business, groceries, utilities, rent, loan repayments, and more.
2. **Account & Payment Modes**:
   - **Cash in Hand** (tracks net cash balance)
   - **Credit Card** (tracks billed expenses & dues)
   - **Money Borrowed** (tracks incoming borrowed loans and outgoing debt repayments with net balance)
   - **Bank / UPI**
3. **Daily Credit & Debit Tracking**:
   - Entering an income credits today's income and updates monthly balance.
   - Entering an expense debits today's debits and tracks budget velocity.
4. **100% Offline Local Mobile Storage**:
   - All transactions and budget limits are stored locally on the device (LocalStorage / IndexedDB).
   - Zero servers, 100% private.
   - Export JSON Backup directly to phone storage.
   - Export CSV spreadsheet for Excel / Sheets.
   - Restore backup file anytime.

---

## 3 Easy Ways to Install & Run on Android:

### Method 1: Instant 1-Tap Install (No APK build needed - PWA)
1. Transfer `index.html` to your Android device or host it via GitHub Pages.
2. Open it in Chrome on your Android phone.
3. Tap the Chrome menu (`⋮`) and select **"Add to Home screen"** or **"Install app"**.
4. The app installs as a native standalone Android app with icon, splash screen, and full offline storage!

### Method 2: Convert to Standalone APK using Web2Apk / PWABuilder (1-Click)
1. Go to [PWABuilder.com](https://www.pwabuilder.com) or use **Website2APK**.
2. Upload this package or enter the hosted URL.
3. Click **"Package for Android"** -> downloads the signed `.apk` file directly to install on your phone.

### Method 3: Build Native APK using Capacitor / Android Studio
Run the following in your terminal:
```bash
npm install -g @capacitor/cli @capacitor/core @capacitor/android
mkdir www && cp index.html manifest.json sw.js www/
npx cap add android
npx cap copy
npx cap open android
# In Android Studio, click Build -> Build APK(s)
```
