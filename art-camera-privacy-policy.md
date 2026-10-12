# Privacy Policy for Art Camera & Cartoon Studio

**Last Updated:** October 12, 2026  
**Effective Date:** October 12, 2026  
**Developer / Publisher:** OcenSoft (Harmil Goti)  
**Application:** Art Camera & Cartoon Studio (`com.ocensoft.artcamera`)

---

## 1. Introduction & Core Privacy Promise

At **OcenSoft**, we believe your creative photography and personal moments belong strictly to you. **Art Camera & Cartoon Studio** is architected from the ground up as a **privacy-first, on-device computational photography application**.

> **Our Fundamental Promise:**  
> All neural segmentation, AI portrait depth calculations, cartoon shaders, and image processing happen **100% locally on your device**. We do **not** upload, store, transmit, analyze, or share your photos or biometric facial information with external servers, cloud providers, or third parties.

---

## 2. Information We Collect and Process

### A. Camera and Photo Data (Strictly On-Device)
- **Photos & Visual Content:** When you take photos or edit pictures within the app, the visual data is processed exclusively in the memory of your local device using embedded **TensorFlow Lite (TFLite)** neural networks and hardware-accelerated shaders.
- **Biometric / Facial Data:** When applying bokeh portrait effects, the neural model identifies human silhouettes and boundaries for depth-of-field simulation. This geometric segmentation mask is generated in temporary memory on-device and is **never** used for facial recognition, identity verification, or biometric profiling.

### B. Device & Operational Information (AdMob & Diagnostics)
The app integrates Google Mobile Ads SDK (AdMob) to support development. Google AdMob may automatically collect limited technical data:
- IP address (used for coarse geographic ad localization)
- Device model, operating system version, and screen metrics
- Google Advertising ID (GAID / IDFA) — subject to user opt-out in OS settings
- Crash diagnostics and performance metrics

For further details on how Google processes ad data, please refer to:  
[Google Privacy & Terms](https://policies.google.com/technologies/ads)

---

## 3. Permissions Requested & How They Are Used

Art Camera only requests operating system permissions strictly required for core functionality:

| Permission | Technical Name | Purpose |
| :--- | :--- | :--- |
| **Camera** | `android.permission.CAMERA` | Required to provide the live camera viewfinder, switch lenses, and capture photos. |
| **Media Library / Storage** | `android.permission.READ_MEDIA_IMAGES` / `WRITE_EXTERNAL_STORAGE` | Required when you choose to export, download, or save captured photos to your phone's photo gallery. |
| **Internet & Network State** | `android.permission.INTERNET`, `ACCESS_NETWORK_STATE` | Used solely to retrieve updated remote configuration rules (ad frequency limits, version checks) and serve non-intrusive advertisements. |

---

## 4. Ads and Monetization Policy

To provide a professional photography experience:
- **No Ads During Photography:** Interstitial ads and banners are **strictly prohibited** during camera capture, live preview, and photo editing workflows.
- **Frequency Capping:** Any ads shown in gallery or wallpaper browsing are capped with strict cooldown timers (minimum 180 seconds) to ensure an enjoyable user experience.
- You can reset or personalize your advertising preferences at any time in your device's Android/iOS system settings.

---

## 5. Third-Party Services

The application may interact with the following trusted third-party services:
1. **Google Mobile Ads (AdMob):** Monetization SDK ([Privacy Policy](https://policies.google.com/privacy)).
2. **GitHub (Raw Content):** Anonymous retrieval of public configuration schemas (`minRequiredVersion`, cooldown intervals).

We do **not** sell, rent, trade, or transfer your personal data to any external parties.

---

## 6. Data Retention and Deletion

- **Photos:** Stored locally in your application cache or device photo gallery. You have full control to view, export, or delete any photo at any time directly through the app or your native gallery app.
- **Temporary Cache:** Neural masks and temporary rendering caches are discarded as soon as processing completes.
- Uninstalling the application completely removes all locally cached application assets.

---

## 7. Children's Privacy (COPPA & GDPR Compliance)

Art Camera does not knowingly collect, request, or solicit personal data from children under the age of 13 (or under 16 in the European Union). Because our computational photography pipeline runs entirely offline on your hardware, no children's data is ever gathered or stored.

---

## 8. Security

We take the security of your data seriously. By keeping all neural processing offline and on-device, your photos are never exposed to transmission vulnerabilities or external cloud data breaches.

---

## 9. Changes to This Privacy Policy

We may periodically update this Privacy Policy to reflect app updates or regulatory requirements. Any modifications will be posted with an updated "Last Updated" date. Continued use of Art Camera after revisions constitutes acceptance of the updated policy.

---

## 10. Contact Us

If you have questions, feedback, or inquiries regarding this Privacy Policy or your privacy while using Art Camera, please contact us at:

- **Developer:** Harmil Goti (OcenSoft)
- **Email:** support@ocensoft.com
- **GitHub Repository:** [https://github.com/harmil007/art-camera](https://github.com/harmil007/art-camera)
