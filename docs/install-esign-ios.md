# How to Download and Install ESign iOSRED on iPhone and iPad (2026–2027)

ESign iOSRED is a customized on-device IPA signing app. Installation depends on the certificate used to sign the ESign app itself and Apple's device provisioning rules.

## Step 1 — Obtain a trusted build

Download from [iOSRED](https://iosred.com) or a verified GitHub release linked from the repository README. Check its version and source. A `.ipa` download alone is not an installed app.

## Step 2 — Install with a supported signing method

Use a signing/install method or use our online ipa signer. The ESign `.ipa` must be signed with a valid certificate/provisioning profile applicable to your device. Follow the on-device prompts to trust or authorize the developer only when you know the source.

## Step 3 — Add a certificate

You can import a compatible `.p12` and `.mobileprovision`, or follow the [iOSRED certificate sync guide](cloud-certificate-sync.md).

## Step 4 — Sign and install your IPA

Import an IPA you have rights to use, choose a compatible certificate/profile, sign it, and follow the app's installation steps. 

## Deep-link formats

ESign iOSRED registers `iosred://`. Depending on the installed build, examples include:

```text
iosred://source/https://example.com/repository.json
iosred://install/https://example.com/application.ipa
iosred://import-certificate?url=https%3A%2F%2Fexample.com%2Fcertificate.ESignCert
```

Use URL encoding for query parameter values. Browser gesture, app route handling, response content type, and authentication can affect whether a link actually performs the action. Launching the app does not prove the import succeeded.

## Supported iOS versions
from iOS 15 to

**iOS 27:** 

See [ESign troubleshooting](esign-not-working.md) for installation errors.
