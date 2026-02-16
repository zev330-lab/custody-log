# 🛡️ CustodyLog — Private Incident Documentation Tracker

A free, private, mobile-first web app for documenting custody-related incidents. Works on **Android, iPhone, and any browser**. No account needed. No data leaves the device.

---

## What It Does

- **Log incidents instantly** — 16 categories covering everything from emotional outbursts to court order violations
- **Severity levels** — Low, Medium, High, Critical
- **Track key details** — date/time, location, witnesses, whether children were present
- **Search & filter** your log
- **Export attorney-ready reports** — formatted HTML (print to PDF), CSV for spreadsheets, JSON backup
- **PIN protection** — optional PIN lock for privacy
- **Works offline** — once loaded, no internet needed
- **Add to Home Screen** — looks and feels like a native app on Android

---

## Incident Categories

| Category | What to Track |
|---|---|
| 🔴 Emotional Outburst | Screaming, rage, throwing things, verbal abuse |
| ⚠️ Threats / Intimidation | Direct or indirect threats, menacing behavior |
| 🔄 Custody Exchange Issue | Late pickups/dropoffs, no-shows, wrong locations |
| ⚖️ Court Order Violation | Breaking specific terms of custody agreement |
| 💬 Hostile Communication | Abusive texts/emails/voicemails |
| 🚨 False Accusation | CPS reports, abuse claims, lies to school/doctors |
| 🚧 Boundary Violation | Showing up unannounced, contacting employer |
| 💔 Alienation Behavior | Badmouthing, undermining, loyalty conflicts |
| 👶 Children's Wellbeing | What kids report, behavioral changes, emotional state |
| 🏠 Neglect / Safety Concern | Unsafe conditions, lack of supervision |
| 🍷 Substance Abuse | Evidence of drug/alcohol use during parenting time |
| 💰 Financial Issue | Withholding support, unauthorized expenses |
| 📵 Harassment / Stalking | Unwanted contact, following, monitoring |
| 👁️ Witness Observation | What third parties saw or reported |
| ✅ Positive Interaction | Good exchanges (shows good faith, important for court) |
| 📝 Other / General Note | Anything else worth documenting |

---

## How to Deploy (Step by Step)

### You need:
- A GitHub account (free at github.com)
- A computer with a terminal/command line

### Steps:

**1. Install Git** (if you don't have it)
- Mac: It's usually pre-installed. Open Terminal and type `git --version`
- Windows: Download from https://git-scm.com/download/win

**2. Create a GitHub repository**
- Go to https://github.com/new
- Name it something like `custody-log` (or anything you want)
- Make it **Public** (required for free GitHub Pages)
- Do NOT check "Add a README" — leave it empty
- Click "Create repository"

**3. Open your terminal and run these commands:**

Replace `YOUR_USERNAME` with your actual GitHub username:

```bash
# Navigate to where you downloaded the app files
cd path/to/custody-tracker

# Initialize git and push
git init
git add .
git commit -m "Deploy CustodyLog"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/custody-log.git
git push -u origin main
```

**4. Enable GitHub Pages**
- Go to your repository on GitHub
- Click **Settings** (tab at top)
- Click **Pages** (in left sidebar)
- Under "Source", select **main** branch
- Click **Save**
- Wait 1-2 minutes

**5. Your app is live!**
- URL will be: `https://YOUR_USERNAME.github.io/custody-log/`

### Share with your friend:
- Send him that URL
- Tell him to open it in Chrome on his Android phone
- Tap the ⋮ menu → "Add to Home Screen"
- It will appear as an app icon on his phone

---

## Privacy & Security Notes

- **All data stays on the device** — nothing is sent to any server
- GitHub Pages only hosts the app code — no user data is stored there
- Optional PIN lock protects against casual access
- **IMPORTANT**: Clearing browser data or uninstalling deletes everything
- **Always export backups regularly** (JSON backup option in Export tab)
- The exported report includes entry IDs and timestamps for credibility

---

## Tips for Effective Documentation

1. **Log immediately** — Document incidents as close to real-time as possible
2. **Be factual** — Write what you saw, heard, or received. Avoid opinions.
3. **Be specific** — "She screamed for 10 minutes at pickup at 5:15 PM" not "She was angry"
4. **Note witnesses** — Anyone who saw or heard the incident
5. **Note if children were present** — Courts weigh this heavily
6. **Log positive interactions too** — Shows good faith and balanced documentation
7. **Export regularly** — Back up your data and share reports with your attorney
8. **Screenshot communications** — Use this app to log them with context
9. **Don't editorialize** — Let the facts speak for themselves
10. **Consult your attorney** — Ask what's most important to track in your specific case

---

## Disclaimer

This app is a documentation tool only. It is not legal advice and is not a substitute for working with a qualified family law attorney. Always consult with your attorney about your specific situation.
