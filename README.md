# firefox-android-hardening
Hardened Firefox setings for Android 

1.Firefox:[Beta](https://play.google.com/store/apps/details?id=org.mozilla.firefox_beta),[Nightly](https://play.google.com/store/apps/details?id=org.mozilla.fenix), or [Fennec F-Droid (Recommended)](https://f-droid.org/packages/org.mozilla.fennec_fdroid)

2.Add-ons:uBlock Origin,NoScript

3.Settings:
HTTPS Only Mode=All Tabs
Enhanced Tracking Protection=Strict
Show Search Suggestion:Off
Search Engine:DuckDuckGo
Homepage>Shortcuts:Off
Private Tabs:On
Open links in a Private Tabs:On

4.about:config
Fingerprinting 
privacy.resistFingerprinting:true
privacy.resistFingerprinting.block_mozAddonManager:true

Disabling WebRTC (Meeting website may not working)
media.peerconnection.enabled=false

Disable safebrowsing
browser.safebrowsing.phishing.enabled=false
browser.safebrowsing.malware.enabled=false

5.Add-ons settings
NoScript
Default/Trusted:script,object,media,frame,font,webgl,fetch
Untrusted:Uncheck all
Cross-tab identity leak protection:Enabled Everywhere
Sanitize cross-site suspicious requests:ON

uBlock Origin
Built-in:All
Ads:EasyList/AdGuard Base,AdGuard Mobile Ads
Privacy:EasyPrivacy/[AdGuard Tracking Protection](abp:subscribe?location=https%3A%2F%2Ffilters.adtidy.org%2Fextension%2Fublock%2Ffilters%2F3.txt&title=AdGuard%20Tracking%20Protection%20Filter%20(uBlock%20Origin)),AdGuard URL Tracking Protection,Block Outsider Intrusion into LAN
Malware:Online Malicious URL Blocklist,Phishing URL Blocklist,PUP Domains Blocklist
