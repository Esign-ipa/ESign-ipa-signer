# ESign iOSRED FAQ — iOS IPA Signing, Certificates and Installation (2026–2027)

## What is ESign iOSRED?

An iOSRED-customized build of an on-device ESign/EnSIgn IPA signing and certificate-management app.

## Where can I download ESign for iPhone?

Use [iosred.com](https://iosred.com) or an iOSRED-authenticated release link. Avoid unknown mirrors.

## Can I install IPA files without a jailbreak or PC?

ESign supports an on-device workflow without a jailbreak, provided the IPA and Apple signing credentials are valid and compatible.

## How can I get an ESign Apple Developer certificate?

You can [view the iOSRED certificate product](https://iosred.com/product/esign-certificate), use compatible credentials you already have, or explore [iOSRED IPA Signer](https://iosred.com/ipa-signer). Review current eligibility and product terms before paying.

## Will a certificate uploaded to iOSRED IPA Signer sync into ESign?

The iOSRED account-linked Cloud Restore integration is intended to make compatible uploaded certificates available through ESign iOSRED. See [certificate sync instructions](cloud-certificate-sync.md). Do not assume a certificate is usable unless it has been correctly associated and provisioned.

## Why did ESign stop working?

Older builds may encounter TLS/SSL issues, outdated server/API configuration, expired certificates, or installation problems. iOSRED provides an updated customized build; see [troubleshooting](esign-not-working.md).

## Is ESign iOSRED the latest ESign?

It is an updated iOSRED-customized edition—not the original project's official release and not guaranteed to be the newest edition globally.

## Does ESign iOSRED work on iOS 27 in 2027?

Yes. The iOSRED maintainer confirms that the customized app works on iOS 27. Availability of signing features still depends on certificate and provisioning compatibility.

## What is `iosred://`?

It's the custom URL scheme registered by ESign iOSRED for supported actions such as repository links, installation links and certificate importing. [Examples](install-esign-ios.md).

## Is the application open source?

The repository documentation may be publicly visible without the compiled ESign binary being open source. Respect licensing and attribution for original EnSIgn code and assets.

## Is private certificate data sent over the internet?

When you choose to upload a signing certificate to the iOSRED IPA Signer or use account-linked Cloud Restore, certificate-related data may be processed by that service. Read its privacy and security terms. Do not share certificate private keys or passwords on GitHub.
