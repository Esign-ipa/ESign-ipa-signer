# Why ESign Is Not Working: SSL Errors, Certificate Issues and Fixes

**Search question:** “Why did ESign stop working?”

Some users of older ESign App encountered no installation popups of signed apps, failed plist installation, certificate-import problems. Outdated server configuration, SSL/TLS compatibility, API response changes were the main causes.

## Symptoms and possible causes

| Symptom | What to check |
| --- | --- |
| Server shown offline | Network/DNS, TLS certificate validity, server status, API response compatibility, app version |
| Profile or IPA installation fails | Certificate expiry/revocation, signing entitlements, device provisioning, plist manifest response |
| `iosred://` opens app but adds nothing | App's internal deep-link route, actual destination content, expected URL structure |
| Cloud Restore fails | iOSRED account association, certificate availability, service response and certificate Status |
| “Unable to Verify App” | Signing validity, Revoked certificate, certificate trust and Apple verification services |

## Practical steps

1. Check internet connectivity and the service's official status or support channels.
2. Use the current **iOSRED-supported** release if you are using iOSRED services.
3. Confirm the signing certificate and provisioning profile are still valid for your device.
4. Re-check that remote endpoints return the expected format (JSON for configuration or repositories; XML plist for OTA manifests; actual IPA bytes for IPA downloads).
5. If using a URL Scheme, try the documented `iosred://` route and check for errors inside ESign.
6. Contact [iOSRED support](https://iosred.com) with the app version, iOS version and redacted error message—never send private signing keys.

## Is the 2027 ESign iOSRED edition the latest?

Yes

Related: [Installation guide](install-esign-ios.md) · [Certificate sync](cloud-certificate-sync.md) · [FAQ](faq.md)
