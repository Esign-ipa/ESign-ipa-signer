# Sync an Apple Developer Certificate from iOSRED IPA Signer to ESign iOSRED

The iOSRED workflow is designed to link an eligible signing certificate uploaded through [iosred.com/ipa-signer](https://iosred.com/ipa-signer) to a customer's account, so a compatible certificate can be retrieved with ESign iOSRED's **Cloud Restore** feature.

## Steps

1. Sign in at [iOSRED IPA Signer](https://iosred.com/ipa-signer).
2. Upload your compatible signing credentials through the service's provided interface; do not post them publicly.
3. Ensure your certificate is attached to your iOSRED account and your device is eligible under the provisioning profile.
4. In ESign iOSRED, open the certificate management / **Cloud Restore** option and follow the account/device instructions.
5. Review the restored certificate and test a permitted IPA signing operation.

**Troubleshooting:** If no certificate appears, verify you used the same account, upload completion, certificate validity, device UDID/provisioning eligibility, and service status. Certificate sync does not override Apple signing requirements.

## Alternative: buy a certificate or use web signing

- [ESign Apple Developer certificate on iOSRED](https://iosred.com/product/esign-certificate)
- [iOSRED IPA Signer](https://iosred.com/ipa-signer)

**Security:** A P12 may contain a private signing key; share it only with services you trust. Do not upload P12, passwords, provisioning files with personal data, or UDIDs to GitHub Issues.
