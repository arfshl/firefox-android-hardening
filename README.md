# firefox-android-hardening
Hardened Firefox setings for Android 

1.Firefox:[Beta](https://play.google.com/store/apps/details?id=org.mozilla.firefox_beta),[Nightly](https://play.google.com/store/apps/details?id=org.mozilla.fenix), or [Fennec F-Droid](https://f-droid.org/packages/org.mozilla.fennec_fdroid)

2.Add-ons:uBlock Origin,NoScript

3.Settings:

- HTTPS Only Mode:All Tabs

- Enhanced Tracking Protection:~Strict~ Standard (ETP is sending do not track header when set to strict,do not track header can be used for fingerprinting)

- Show Search Suggestion:Off

- Search Engine:DuckDuckGo

- Homepage>Shortcuts:Off

- Private Tabs:On

- Open links in a Private Tabs:On

4.about:config

- Fingerprinting 

privacy.resistFingerprinting:true

privacy.resistFingerprinting.block_mozAddonManager:true

privacy.resistFingerprinting.autoDeclineNoUserInputCanvasPrompts:true

privacy.resistFingerprinting.exemptedDomains:*.example.invalid

privacy.resistFingerprinting.jsmloglevel:Warn

privacy.resistFingerprinting.randomDataOnCanvasExtract:true

privacy.resistFingerprinting.reduceTimerPrecision.jitter:true

privacy.resistFingerprinting.reduceTimerPrecision.microseconds:1000

privacy.resistFingerprinting.target_video_res:480

privacy.resistFingerprinting.testGranularityMask:0


- Disable WebRTC (Meeting website may not working)

media.peerconnection.enabled:false

- Enable Fission

fission.autostart:true


5.Add-ons settings

- NoScript

Default/Trusted:script,object,media,frame,font,webgl,fetch

Untrusted:Uncheck all

Cross-tab identity leak protection:Enabled Everywhere

Sanitize cross-site suspicious requests:ON

- uBlock Origin

Built-in:All

Ads:EasyList,AdGuard Base,AdGuard Mobile Ads

Privacy:EasyPrivacy,AdGuard URL Tracking Protection,AdGuard Tracking Protection,Block Outsider Intrusion into LAN

Malware:Online Malicious URL Blocklist,Phishing URL Blocklist,PUP Domains Blocklist