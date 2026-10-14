# HamiDebt Android v3.6.4

Corrected verified in-place update for the existing **طلب و بدهی حامی** app.

- applicationId: `ir.hamigallery.debt`
- versionCode: `100`
- versionName: `3.6.4`
- Signing certificate SHA-256: `719a543a012c20f7c33dd3b0c6f42b8dd61fc606cd789db0c96ef3576951e8f7`
- Same signing certificate as the known working v3.6.1 APK.
- versionCode is deliberately above the legacy installed build (43), so Android treats this as an update rather than a downgrade.
- Phone remains accounting source of truth.
- SMS: send by SIM / copy text / do not send.
- Customer and colleague gold purchases support full / partial / no physical receipt with ledger effects.
- Do not uninstall the current app before installing this update.

**Do not install v3.6.3.** It used a lower versionCode than the installed legacy build and Android rejected it.
