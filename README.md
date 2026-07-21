PRIVACY POLICY
Pocket Spotter

Effective date: July 21, 2026
Last updated: July 21, 2026

This Privacy Policy describes how Pocket Spotter (“the App,” “we,” “us,” or “our”) handles information when you use the mobile application Pocket Spotter (Android package: com.pocketspotter.app).

By using the App, you agree to this Privacy Policy. If you do not agree, please do not use the App.


1. WHO WE ARE / CONTACT

Pocket Spotter is a mobile application for precision rifle shooters. It stores your DOPE (Data On Previous Engagements) cards, target cards, and related settings primarily on your device.

Privacy contact email: PocketSpotter@gmail.com

If you have questions about this Privacy Policy or your information, contact us at the email above.


2. SUMMARY (PLAIN LANGUAGE)

- Most of your data stays on your phone. DOPE cards, DOPE table entries, target cards, and app settings are stored locally on your device.
- Pocket Spotter does not operate any servers, cloud accounts, cloud sync, or remote backup. We do not receive your DOPE data, voice audio, or location on any infrastructure we run.
- We do not require an account.
- We do not use advertising SDKs, analytics SDKs, or crash-reporting SDKs in the App.
- Voice commands are processed on your device using an offline speech-recognition model (Vosk). Microphone audio for recognition is not sent anywhere by the App — not to us, and not to any speech service.
- Spoken responses use on-device text-to-speech provided by your device’s system speech engine.
- Optional weather autofill: if you tap “Auto-Fill from My Location” on a card, the App requests your approximate location and sends your latitude and longitude to MET Norway (the Norwegian Meteorological Institute) to retrieve local temperature, humidity, and pressure. This only happens when you use that feature and grant location permission. That request goes to MET Norway, not to Pocket Spotter.
- If you export or share files (for example CSV exports) through your device’s share sheet, the destination is chosen by you (email, Drive, messaging apps, etc.). That sharing is controlled by you and the apps you select.


3. INFORMATION THE APP HANDLES

3.1 Information you create and store on your device

The App stores the following on your device (using local database and local preferences storage), for example:

- DOPE card details you enter (such as card name, firearm, cartridge/bullet information, ballistic coefficient, muzzle velocity, sight height, zero distance, twist information, weather/environment fields, notes, and related unit preferences)
- DOPE table entries (distances and hold values you enter, import, generate, or interpolate)
- Target cards used for ranging (title, description, dimensions)
- App settings (such as theme, microphone source preference, voice/TTS preferences, wind-direction display format, aerodynamic-jump setting, and similar preferences)

This information is stored locally so the App can function offline. It is not sent to us. Pocket Spotter does not operate servers, accounts, or a cloud service that would receive this data.

3.2 Information processed for voice features (on device)

If you use Active Mode voice features, the App may process:

- Microphone audio, to recognize voice commands on your device
- Temporary recognition results / transcripts needed to carry out commands and speak responses

Speech recognition is performed on-device with the bundled Vosk offline model. Recognition audio is not sent by the App to us or to any external speech service. Pocket Spotter does not operate servers that collect audio.

Spoken feedback uses your device’s text-to-speech engine (via the Expo Speech / system TTS pathway). That processing occurs through your device’s speech capabilities.

3.3 Optional location and weather information

Only if you choose weather autofill and grant permission, the App may:

- Obtain your current location (latitude/longitude) from your device
- Optionally read device sensors such as barometer (pressure) and GPS altitude to improve local card fields when available
- Send latitude and longitude to MET Norway’s Locationforecast API (api.met.no), along with a User-Agent identifying the App, to request current temperature, relative humidity, and pressure
- Write the resulting values (and altitude when available) into the card fields you are editing

Location is requested for this feature when needed. The App does not keep a location history for advertising or tracking.

3.4 Information we do not collect through the App

The App does not:

- Require you to create an account or sign in
- Sell your personal information
- Show in-app ads through advertising networks
- Include third-party analytics or crash-reporting SDKs that report usage to us
- Continuously track your location in the background for weather or other purposes


4. HOW INFORMATION IS USED

We use the information described above only to provide App features you request, including:

- Creating, editing, locking, duplicating, importing, exporting, and displaying DOPE cards and entries
- Target ranging calculations
- Active Mode voice commands and spoken responses
- Optional screen-off / background listening while an Active Mode session is running (foreground service / notification as required by Android)
- Optional Bluetooth headset microphone routing when you choose that option
- Optional weather autofill for ballistics-related environmental fields
- Saving your preferences so the App works the way you configured it

We do not use your DOPE data, voice audio, or location for advertising.


5. HOW INFORMATION IS SHARED

5.1 Sharing by the App to third parties

The App shares information with a third party only in this limited case:

- MET Norway (api.met.no): when you use weather autofill, the App sends your latitude and longitude as part of the weather request, and identifies the App with a User-Agent header required by MET Norway. MET Norway processes that request according to its own terms and privacy practices. Review MET Norway’s terms at: https://api.met.no/doc/TermsOfService and MET Norway’s privacy information via https://www.met.no/

5.2 Sharing you initiate

If you use export/share features (CSV, zip of cards, or any debug/share text), your device’s system share sheet lets you send files or text to another app or service you choose. Those recipients are outside our control. Only share information with parties you trust.

5.3 Legal and safety

Pocket Spotter does not operate a backend that receives your App content. If we later receive information from you directly (for example by email support), we may use it to respond to you and may disclose it if required by law, legal process, or to protect rights, safety, and security.


6. PERMISSIONS (ANDROID)

Depending on your device and Android version, the App may request permissions such as:

- Microphone (RECORD_AUDIO): to listen for voice commands in Active Mode
- Notifications: to show an Active Mode / listening status notification when required
- Foreground service / microphone-related foreground service: to continue listening while the screen is off during an Active Mode session, as permitted by Android rules
- Bluetooth connect: to use a Bluetooth headset microphone when you select that option
- Modify audio settings / wake lock: to support reliable audio routing and listening behavior
- Location (when in use): only for optional weather autofill after you choose that feature
- Internet / network access: to contact MET Norway when you use weather autofill (and for ordinary OS networking). Core DOPE and voice recognition features are designed to work without an internet connection.

You can deny or revoke permissions in Android Settings. Some features will not work without the related permission.


7. DATA RETENTION AND DELETION

- Local App data remains on your device until you delete it in the App (for example deleting a card or entry) or uninstall the App / clear App storage.
- Uninstalling the App or clearing App data removes local database and preference data stored by the App on that device (subject to normal Android behavior).
- Weather autofill requests go to MET Norway, not to Pocket Spotter. We do not store those requests because we do not operate servers. Any retention by MET Norway is governed by MET Norway’s practices.
- If you email us, we retain that correspondence as needed to respond and for ordinary business/legal records.


8. SECURITY

We design the App to keep your shooting data on your device. No method of electronic storage is 100% secure. Protect your phone with a screen lock and be careful when exporting or sharing files.


9. CHILDREN’S PRIVACY

The App is intended for adults and is not directed to children under 13 (or the equivalent minimum age in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided personal information to us (for example by emailing us), contact us and we will take appropriate steps to delete it.


10. INTERNATIONAL USERS

The App stores most information on your device. If you use weather autofill, your coordinates are sent to MET Norway (the Norwegian Meteorological Institute) in Norway. Your use of that feature may involve processing outside your country.


11. YOUR CHOICES AND RIGHTS

Depending on where you live, you may have rights regarding personal information, such as access, correction, deletion, or objection. Because most App content is stored only on your device, the practical way to access, edit, or delete that content is inside the App (edit/delete cards and entries) or by uninstalling the App / clearing App storage.

For requests about information you sent us by email, or questions about this Policy, contact: PocketSpotter@gmail.com

If you are in the EEA/UK, you may also have the right to lodge a complaint with your local supervisory authority.


12. THIRD-PARTY SERVICES AND LINKS

This Policy applies to Pocket Spotter. Third-party services (including MET Norway and any apps you share files with) have their own policies. We are not responsible for their practices.


13. CHANGES TO THIS POLICY

We may update this Privacy Policy from time to time. The “Last updated” date at the top will change when we do. Continued use of the App after an update means you accept the revised Policy. For material changes, we may provide additional notice in the App or on the page where this Policy is posted.


14. GOOGLE PLAY DATA SAFETY ALIGNMENT (FOR YOUR CONVENIENCE)

This section is a plain-language summary to help keep your Google Play Data safety answers consistent with this Policy. Always complete Play Console based on the live App behavior.

Data collected / shared by the App (as designed today):

- Approximate location: collected and shared with MET Norway only when the user uses weather autofill and grants permission. Purpose: App functionality (environmental fields for ballistics). Not sold. Not used for ads. Not sent to Pocket Spotter (we do not operate servers).
- Audio (microphone): processed on device for voice commands. Not sent anywhere by the App — not to us and not to any speech service. Purpose: App functionality.
- App content / user-generated content (DOPE cards, entries, target cards, settings): stored on device. Not transmitted by the App to us. May leave the device only if the user exports/shares it.
- Device or other identifiers for analytics/advertising: not collected by the App for ads/analytics (no such SDKs).

Encryption / security: data at rest is protected by the device’s normal app sandbox and any device encryption the user enables.

Deletion: users can delete content in-app or uninstall/clear App data.


15. DEVELOPER INFORMATION

App name: Pocket Spotter
Android application ID: com.pocketspotter.app
Privacy contact: PocketSpotter@gmail.com


END OF PRIVACY POLICY
