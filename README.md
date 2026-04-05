<!-- <h1 align="center">Hi there, I'm Amar Agrawal! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"></h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2196F3&center=true&vCenter=true&width=435&lines=Full+Stack+Developer+(MERN);Mechatronics+Engineer;SaaS+Builder;GFG+Campus+Ambassador" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://amarjec.netlify.app/">
    <img src="https://img.shields.io/badge/🌐_Visit_My_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/amarjec/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" />
  </a>
  <a href="mailto:amar208320@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail" alt="Email" />
  </a>
</p>

<p align="center">
  <i>"Aligning technical solutions with business needs."</i>
</p>

---

### 👨‍💻 About Me

I am a final-year **Mechatronics Engineering** student at **Jabalpur Engineering College (JEC)** with a strong focus on building scalable SaaS applications. I combine system design with full-stack development to solve real-world inefficiencies.

* 🧠 **Problem Solving:** Solved **800+ DSA problems** across LeetCode & GeeksforGeeks.
* 🏆 **Leadership:** Selected as **Campus Ambassador for GeeksforGeeks** (2024-2025).
* 🔭 **Currently Building:** **Billing Habit**, a SaaS deployed on the **Indus App Store**.
* ⚡ **Fun fact:** I enjoy strategic **Chess** ♟️ matches.

---

### 🚀 Featured SaaS Projects

#### 1. 🧾 [Billing Habit](https://billinghabit.vercel.app) *(Business Billing SaaS)*
> *A MERN-based Progressive Web App (PWA) enabling businesses to manage billing and profit analysis.*
* **Impact:** Slashed transaction time by **~90%+**, allowing invoice generation in 2-3 minutes.
* **Key Features:**
  * 🔐 **Security:** Secure profit analysis protected by 4-digit PIN.
  * 💳 **Payments:** Integrated **Razorpay** for live subscription workflows.
  * 📱 **Deployment:** Live on **Indus App Store** & Web.
* **Tech Stack:** MERN Stack, Google Auth, JWT.

#### 2. 🎨 [Imagify](https://imagify-frontend-gjzn.onrender.com) *(AI Image Generation Platform)*
> *A full-stack text-to-image generation platform with a credit-based system.*
* **Core Logic:** Implemented a credit-control system to limit and manage user API usage.
* **Security:** Secured user data and private routes using **JWT and bcrypt**.
* **Tech Stack:** MERN, Third-party AI APIs, Stripe/Razorpay.

---

### 🛠️ Technical Arsenal

<table align="center">
  <tr>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/java-icon.svg" alt="icon" width="65" height="65" />
      <br>Java
    </td>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="65" height="65" />
      <br>JavaScript
    </td>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="65" height="65" />
      <br>React
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=nodejs" width="65" height="65" alt="Node" />
      <br>Node.js
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=express" width="65" height="65" alt="Express" />
      <br>Express
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=mongodb" width="65" height="65" alt="MongoDB" />
      <br>MongoDB
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="MySQL" width="65" height="65" />
      <br>MySQL
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=tailwind" width="65" height="65" alt="Tailwind" />
      <br>Tailwind
    </td>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/aws-icon.svg" alt="AWS" width="65" height="65" />
      <br>AWS
    </td>
     <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=postman" width="65" height="65" alt="Postman" />
      <br>Postman
    </td>
    <td align="center" width="96">
      <img src="https://skillicons.dev/icons?i=vercel" width="65" height="65" alt="Vercel" />
      <br>Vercel
    </td>
    <td align="center" width="96">
      <img src="https://techstack-generator.vercel.app/github-icon.svg" alt="Git" width="65" height="65" />
      <br>Git
    </td>
  </tr>
</table>

---

<p align="center">
  <a href="https://amarjec.netlify.app/"><b>👉 Check out my full Portfolio for more!</b></a>
</p> -->

# KachaBill — Google Play Publisher Guide
### Complete Step-by-Step Reference (Do This When Ready to Publish)

---

## SECTION 1 — WILL THE APP WORK WITHOUT THESE STEPS?

**Short answer: YES — everything works except payments.**

Here is exactly what works and what doesn't before you complete setup:

| Feature | Works Without Play Account? |
|---|---|
| Google Login (Owner) | ✅ Yes |
| Staff Login | ✅ Yes |
| Billing / Invoices | ✅ Yes |
| Khata / Ledger | ✅ Yes |
| Inventory Management | ✅ Yes |
| PDF Invoice Generation | ✅ Yes |
| Analytics | ✅ Yes (for trial users) |
| Recycle Bin | ✅ Yes (for trial users) |
| Staff Management | ✅ Yes (for trial users) |
| 90-day free trial on signup | ✅ Yes — works fully |
| **Premium subscription purchase** | ❌ No — needs Play Console |
| **Subscription renewal webhook** | ❌ No — needs Pub/Sub setup |
| **Subscription restore on reinstall** | ❌ No — needs active product IDs |

**Bottom line:** New users get a 90-day free trial automatically. Your app is fully functional for all users during that period. Only the "Upgrade to Premium" flow is blocked until you complete the Play Console setup.

---

## SECTION 2 — ADD ONE LINE TO YOUR FRONTEND .env

Before building, add this to your `.env` file in the Expo project root:

```
EXPO_PUBLIC_PACKAGE_NAME=com.amarjec.paperbill
```

This was the only remaining code issue — `subscription.jsx` and `payment.controller.js` had `com.yourcompany.kachabill` hardcoded. Both files are now fixed to use the env var.

---

## SECTION 3 — GOOGLE PLAY CONSOLE SETUP (Do When Ready)

---

### STEP 1 — Create Your Developer Account

1. Go to **https://play.google.com/console**
2. Click **"Get started"**
3. Pay the one-time $25 registration fee
4. Fill in your developer name (this appears publicly on the Play Store)
5. Accept the Developer Distribution Agreement
6. Wait for account approval (usually instant, sometimes up to 2 days)

---

### STEP 2 — Create the App

1. In Play Console, click **"Create app"**
2. App name: **KachaBill**
3. Default language: **English (India)**
4. App or game: **App**
5. Free or paid: **Free** (your monetization is through in-app subscriptions)
6. Accept the declarations
7. Click **"Create app"**

---

### STEP 3 — Set Up In-App Subscriptions

1. Left sidebar → **Monetize → Products → Subscriptions**
2. Click **"Create subscription"**

**Monthly Plan:**
- Product ID: `kachabill_monthly` ← must match exactly what's in your code
- Name: KachaBill Premium Monthly
- Description: Full access to all KachaBill premium features for 1 month
- Billing period: 1 month
- Price: ₹199 (set "India" price in the pricing table)
- Grace period: 3 days (recommended)
- Click **"Save"** then **"Activate"**

**Yearly Plan:**
- Product ID: `kachabill_yearly` ← must match exactly what's in your code
- Name: KachaBill Premium Yearly
- Description: Full access to all KachaBill premium features for 1 year
- Billing period: 1 year
- Price: ₹1,999
- Grace period: 7 days (recommended for annual)
- Click **"Save"** then **"Activate"**

> ⚠️ Both subscriptions MUST be in **Active** status before any user can purchase. Draft status will cause `getSubscriptions()` to return an empty array.

---

### STEP 4 — Set Up Google Play API Access (For Backend Verification)

This allows your server to verify purchase tokens with Google.

1. In Play Console → **Setup → API access**
2. Click **"Link to a Google Cloud project"**
   - If you don't have one: click "Create new project" → name it "KachaBill API"
   - If you have Firebase: link to the same project
3. After linking, click **"Configure Google Play Android Developer API"**
4. You'll be taken to Google Cloud Console
5. Make sure the **"Google Play Android Developer API"** is enabled
   - Go to **APIs & Services → Library** → search "Android Developer" → Enable

**Create Service Account:**
1. In Google Cloud Console → **IAM & Admin → Service Accounts**
2. Click **"+ Create Service Account"**
3. Name: `kachabill-play-api`
4. Description: "Server-side verification of Google Play purchases"
5. Click **"Create and Continue"**
6. Role: Skip (click "Continue" without adding a role)
7. Click **"Done"**

**Grant Play Console permissions:**
1. Go back to **Play Console → Setup → API access**
2. Find your new service account, click **"Grant access"**
3. Role: **"Financial data (read-only)"** — this is enough to verify purchase tokens
4. Click **"Apply"**

**Download the key:**
1. Back in Google Cloud Console → IAM & Admin → Service Accounts
2. Click your service account → **"Keys"** tab
3. **"Add key" → "Create new key" → JSON**
4. Save the downloaded file as: `google-play-service-account.json`
5. Place it in your backend at: `./config/google-play-service-account.json`
6. Add to `.gitignore`: `config/google-play-service-account.json`

**Add to your backend `.env`:**
```
GOOGLE_SERVICE_ACCOUNT_KEY_PATH=./config/google-play-service-account.json
ANDROID_PACKAGE_NAME=com.amarjec.paperbill
```

---

### STEP 5 — Set Up Real-time Developer Notifications (Webhook)

This lets Google notify your server when subscriptions renew, expire, or cancel.

**Create Pub/Sub topic:**
1. Go to **Google Cloud Console → Pub/Sub → Topics**
2. Click **"Create Topic"**
3. Topic ID: `kachabill-play-notifications`
4. Click **"Create"**
5. Copy the full topic name: `projects/YOUR_PROJECT_ID/topics/kachabill-play-notifications`

**Add publish permission:**
1. In the topic you just created, click **"Add principal"**
2. Principal: `google-play-developer-notifications@system.gserviceaccount.com`
3. Role: **Pub/Sub Publisher**
4. Click **"Save"**

**Create Subscription (Push endpoint):**
1. In Pub/Sub → **Subscriptions → Create Subscription**
2. Subscription ID: `kachabill-webhook`
3. Select the topic you created
4. Delivery type: **Push**
5. Endpoint URL: `https://your-production-server.com/api/payments/google-webhook`
6. Click **"Create"**

**Link to Play Console:**
1. Play Console → **Monetize → Subscriptions → Real-time developer notifications**
2. Paste the topic name from above
3. Click **"Save changes"**
4. Click **"Send test notification"** to verify it works
   - You should see a 200 response in your server logs: `[GoogleWebhook] Test notification received.`

---

### STEP 6 — Build and Upload Your App

```bash
# Login to EAS (first time)
eas login

# Set up keystore (first time — EAS generates and stores it securely)
eas credentials

# Build production AAB
eas build --platform android --profile production

# When build completes, submit to Play Console (internal testing track)
eas submit --platform android --profile production
```

Alternatively, download the `.aab` file from the EAS dashboard and upload it manually in Play Console → **Release → Internal testing → Create new release**.

---

### STEP 7 — Complete Play Console Store Listing

**App content → Privacy policy:**
- URL: Host your legal page content at a public URL
- Quick option: Create a Google Site or Notion page with your legal.jsx content
- Example: `https://sites.google.com/view/kachabill-privacy`

**Store listing:**
- [ ] App title (30 char max): `KachaBill - Shop Billing App`
- [ ] Short description (80 char max): `Fast billing, Khata & inventory for your shop`
- [ ] Full description: paste your app's feature list (4000 char max)
- [ ] App icon: 512×512px PNG — export from your `./assets/images/logo.png`
- [ ] Feature graphic: 1024×500px banner (create in Canva)
- [ ] Screenshots: minimum 2, recommended 4-5 (use Android emulator or real device)

**App content:**
- [ ] Content rating → complete questionnaire → will get **Everyone**
- [ ] Target audience → Age 18+ → Does NOT appeal to children
- [ ] Data safety → fill as described below

**Data Safety form — fill it exactly like this:**
- Does your app collect or share any of the required user data types? **Yes**
- Is all of the user data collected by your app encrypted in transit? **Yes**
- Do you provide a way for users to request that their data is deleted? **Yes**

Data types to declare:
| Data Type | Collected | Shared | Required | Purpose |
|---|---|---|---|---|
| Name | Yes | No | Yes | App functionality |
| Email address | Yes | No | Yes | Account management |
| Phone number | Yes | No | Optional | App functionality |
| Financial info (transactions) | Yes | No | Yes | App functionality |

- Are you sharing any of the data types with third parties? **No**
- Do you use this data for tracking purposes? **No**

---

### STEP 8 — Internal Testing → Production

1. **Internal testing** (immediate, up to 100 testers): Add your own Gmail
2. Test the full subscription flow with a real Google account
3. Use Google's test payment method (not real money during testing)
4. When satisfied → **Promote to production** or **Open testing → Production**
5. First release review takes 1-3 days, subsequent releases are usually faster

---

## SECTION 4 — TESTING SUBSCRIPTIONS WITHOUT REAL MONEY

1. In Play Console → **License testing**
2. Add your Gmail accounts as **License testers**
3. License testers can purchase subscriptions for free and cancel instantly
4. Subscription periods are sped up: 1 month = 5 minutes, 1 year = 30 minutes
5. This lets you test the full renewal/expiry webhook cycle in 30 minutes

---

## SECTION 5 — QUICK REFERENCE: ENV VARS CHECKLIST

**Frontend `.env`:**
```
EXPO_PUBLIC_API_URL=https://your-production-server.com/api
EXPO_PUBLIC_PACKAGE_NAME=com.amarjec.paperbill
EXPO_PUBLIC_GOOGLE_WEB_CLIENT_ID=xxx
EXPO_PUBLIC_GOOGLE_ANDROID_CLIENT_ID=xxx
EXPO_PUBLIC_GOOGLE_IOS_CLIENT_ID=xxx
```

**Backend `.env`:**
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_strong_random_secret
GOOGLE_CLIENT_ID=xxx
ALLOWED_ORIGINS=https://your-frontend-domain.com
NODE_ENV=production
ANDROID_PACKAGE_NAME=com.amarjec.paperbill
GOOGLE_SERVICE_ACCOUNT_KEY_PATH=./config/google-play-service-account.json
```

---

## SECTION 6 — SUMMARY OF ALL CODE CHANGES MADE

| # | Issue | File Changed | Status |
|---|---|---|---|
| 1 | Google Play IAP replacing Razorpay | `subscription.jsx`, `payment.controller.js`, `payment.route.js` | ✅ Done |
| 2 | JWT expiry 1000d → 30d | `auth.controller.js` | ✅ Done |
| 3 | `secure_pin` stripped from login response | `auth.controller.js` | ✅ Done |
| 4 | Hardcoded Razorpay test key removed | `subscription.jsx` | ✅ Done |
| 5 | Rate limiting enabled | `app.js` | ✅ Done |
| 6 | `helmet` added | `app.js` | ✅ Done |
| 7 | Hardcoded `com.yourcompany.kachabill` in payment | `payment.controller.js` | ✅ Done |
| 8 | Hardcoded `com.yourcompany.kachabill` in subscription | `subscription.jsx` | ✅ Done |
| 9 | AppState refresh cooldown (5 min) | `AuthContext.js` | ✅ Done |
| 10 | `unmountOnBlur` removed, `lazy: true` added | `(tabs)/_layout.jsx` | ✅ Done |
| 11 | Error boundary added | `app/_layout.jsx` | ✅ Done |
| 12 | `totalMarketDebt` shown in ledger | `ledger.jsx` | ✅ Done |
| 13 | Stable device ID via `expo-application` | `useLogin.js`, `staff-login.jsx` | ✅ Done |
| 14 | Google client IDs moved to env vars | `useLogin.js` | ✅ Done |
| 15 | `PremiumLock` simplified to `user?.isPremium` only | `PremiumLock.jsx` | ✅ Done |
| 16 | Google Play webhook handler | `googleWebhook.controller.js` | ✅ Done |
| 17 | `{ new: true, runValidators: true }` added | `bill.controller.js`, `customer.controller.js` | ✅ Done |
