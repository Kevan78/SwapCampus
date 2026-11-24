# SwapCampus — Geoffroy Kevan / Omar Tir

Application mobile **SwapCampus** (II.3510) : domaine Kotlin dans `:shared`, interface **Compose Multiplatform** dans `:composeApp`, lanceur Android `:androidApp`.

## Modules

| Module | Rôle |
|--------|------|
| `shared` | Domaine, catalogues, dépôts (KMP) |
| `composeApp` | UI partagée (`commonMain` / `androidMain` / `iosMain`) |
| `androidApp` | APK Android → `App()` |

## Build

```bash
./gradlew :androidApp:assembleDebug
./gradlew :composeApp:compileKotlinIosSimulatorArm64
./gradlew :shared:testDebugUnitTest
```

Comptes démo : `omar@gmail.com` / `omar123`
