# DD-420 — App Store Submission Checklist
Last updated: May 29, 2026

---

## 🚨 Critical — Submission Blockers

- [x] ~~Xcode 26 / iOS 26 SDK — already installed (v26.2)~~
- [x] ~~PrivacyInfo.xcprivacy — created and added to target~~
- [x] ~~Privacy Policy URL — live at ketchupdrool.github.io/dd420-privacy/privacy-policy.html~~
- [ ] Age rating 17+ — set in App Store Connect → App Information
- [x] ~~PaywallView.swift — full rewrite complete. PaywallViewModel.swift also written.~~

---

## ⚠️ Important — Likely Rejection if Missing

- [ ] Tinted app icon variant — add grayscale icon to Assets.xcassets
- [ ] Screenshots — iPhone 6.7" and 6.1" from Xcode simulator
- [ ] Support URL — add to App Store Connect
- [ ] App Review Notes — explain DD-420 is veteran wellness + harm reduction tool

---

## 🔧 Should Fix — Code Level

- [ ] Accessibility audit — run Xcode Accessibility Inspector on every screen
- [ ] Verify light mode — run every screen in light mode, fix anything broken

---

## ✅ Already Compliant (no action needed)

- All data on-device only — no server, no cloud
- No cross-app tracking — ATT prompt not needed
- No medical claims — enforced in app rules
- 988 Crisis Line free forever — cannot be gated
- Free tier core features — coping tools + check-in always free
- No force-unwrap in production code
- Freemium model — matches Apple IAP requirements

---

## ✅ Feature Gating (confirmed correct)

| Feature | Tier | Notes |
|---|---|---|
| VA Provider Report | PLUS | Full clinical picture — symptoms + cannabis |
| Family/Caregiver Report | FREE | Simple summary for support person |
| Caregiver Sharing (More tab) | FREE | Share wellness summary |
| AI Insights | PLUS | |
| Advanced Charts | PLUS | |
| Tolerance Break Tracker | PLUS | |
| Strain Library | PLUS | |
| Custom Triggers | PLUS | |
| Unlimited History | PLUS | |
| 988 Crisis Line | FREE FOREVER | Cannot be gated |
| Coping Tools | FREE FOREVER | Cannot be gated |
| Daily Check-In | FREE FOREVER | Cannot be gated |

---

Progress: 4 of 11 complete
