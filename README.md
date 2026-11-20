# VATT Wallet — Descargas oficiales · Official downloads

**Español** · [English](#english)

VATT Wallet es una billetera **sin custodia**: tus claves y tu frase de 12 palabras se crean y se guardan solo en tu equipo. Esta es la **única página oficial** para descargar los instaladores.

## ⬇️ Descargar

**Última versión:** https://github.com/VatioVATT/vatt-wallet-releases/releases/latest

Al abrir el enlace, baja hasta **Assets** y elige el archivo de tu equipo:

| Tu equipo | Archivo | Requisitos |
| --- | --- | --- |
| Computadora con Windows | `VATT-Wallet-Setup-X.Y.Z.exe` | Windows 10 u 11 de 64 bits |
| Celular Android | `VATT-Wallet-X.Y.Z.apk` | Android 7.0 o superior |

`X.Y.Z` es el número de versión, por ejemplo `4.11.2`. Los archivos `SHA256SUMS…` no se instalan: sirven para comprobar que el instalador es el original (ver más abajo).

## 💻 Instalar en Windows

1. Descarga `VATT-Wallet-Setup-X.Y.Z.exe` y ábrelo.
2. Si aparece **«Windows protegió su PC»**, haz clic en **Más información** y luego en **Ejecutar de todas formas**. Este aviso aparece porque el instalador todavía no tiene firma de Microsoft; no significa que tenga un virus.
3. Lee y acepta el **acuerdo de licencia**.
4. Elige la carpeta y haz clic en **Instalar** y luego en **Finalizar**. VATT Wallet se abre sola.

## 📱 Instalar en Android

1. Desde el celular, descarga `VATT-Wallet-X.Y.Z.apk`.
2. Ábrelo desde las notificaciones o desde **Archivos → Descargas**.
3. Si Android pide permiso para **instalar apps desconocidas**, actívalo solo para la app con la que abriste el archivo (Chrome o Archivos) y vuelve atrás.
4. Toca **Instalar**. Si Google Play Protect muestra un aviso, toca **Más detalles → Instalar de todas formas**.

> **¿Tenías una versión anterior a la 4.10.15 en Android?** Si aparece «App no instalada», ten a mano tus **12 palabras**, desinstala la versión anterior, instala la nueva y restaura tu billetera. Esto pasa **una sola vez**: desde la 4.10.15, todas las versiones se instalan encima.

## 🔄 Actualizaciones

No tienes que volver a esta página. Cuando haya una versión nueva, la app te mostrará **«Nueva versión disponible»**:
- **Windows:** haz clic en **Actualizar**. La app descarga el instalador, comprueba la firma de VATT Wallet y lo instala.
- **Android:** toca **Actualizar** y luego **Instalar**. Tu billetera se conserva.

## ✅ Comprobar que el archivo es original (opcional)

Cada versión trae la **huella** (SHA-256) de sus instaladores en `SHA256SUMS-windows.txt` y `SHA256SUMS-android.txt`.

En Windows, abre **PowerShell** en la carpeta de descargas y escribe:

```
Get-FileHash .\VATT-Wallet-Setup-X.Y.Z.exe -Algorithm SHA256
```

El resultado debe ser **exactamente igual** al número que aparece junto al archivo en `SHA256SUMS-windows.txt`. Si no coincide, **no lo instales** y avísanos.

## 🔒 Seguridad

- Descarga VATT Wallet **solo desde esta página**. No instales copias enviadas por chat, correo o redes sociales.
- **VATT Wallet nunca te pedirá tus 12 palabras, tu PIN ni tus claves.** Quien te los pida está intentando robarte.
- Guarda tus 12 palabras en papel, en un lugar seguro, fuera de tu computadora y de tu celular.

## ⚠️ Aviso importante (descargo de responsabilidad)

Tú eres el único y absoluto responsable de tus activos digitales. Si pierdes, olvidas o compartes tu frase de recuperación (12 palabras), tu PIN o tus llaves privadas, nadie podrá recuperar tus fondos: ni VATT Wallet ni ninguna otra persona. VATT Wallet no se hace responsable por pérdidas causadas por la pérdida, el robo o la divulgación de esos datos, ni por las operaciones que firmes. Las operaciones en blockchain son irreversibles. VATT Wallet no ofrece asesoría financiera, legal ni de inversión.

---

## English

VATT Wallet is a **non-custodial** wallet: your keys and your 12-word phrase are created and stored only on your device. This is the **only official page** to download the installers.

## ⬇️ Download

**Latest version:** https://github.com/VatioVATT/vatt-wallet-releases/releases/latest

Open the link, scroll down to **Assets** and choose the file for your device:

| Your device | File | Requirements |
| --- | --- | --- |
| Windows computer | `VATT-Wallet-Setup-X.Y.Z.exe` | Windows 10 or 11, 64-bit |
| Android phone | `VATT-Wallet-X.Y.Z.apk` | Android 7.0 or later |

`X.Y.Z` is the version number, for example `4.11.2`. The `SHA256SUMS…` files are not installed: they let you check that the installer is the original one (see below).

## 💻 Install on Windows

1. Download `VATT-Wallet-Setup-X.Y.Z.exe` and open it.
2. If you see **"Windows protected your PC"**, click **More info** and then **Run anyway**. This notice appears because the installer is not yet signed by Microsoft; it does not mean it contains a virus.
3. Read and accept the **license agreement**.
4. Choose the folder, click **Install** and then **Finish**. VATT Wallet opens automatically.

## 📱 Install on Android

1. On your phone, download `VATT-Wallet-X.Y.Z.apk`.
2. Open it from the notifications or from **Files → Downloads**.
3. If Android asks for permission to **install unknown apps**, allow it only for the app you used to open the file (Chrome or Files) and go back.
4. Tap **Install**. If Google Play Protect shows a warning, tap **More details → Install anyway**.

> **Did you have a version older than 4.10.15 on Android?** If you see "App not installed", have your **12 words** ready, uninstall the old version, install the new one and restore your wallet. This happens **only once**: from 4.10.15 on, every version installs over the previous one.

## 🔄 Updates

You don't need to come back to this page. When a new version is available, the app will show **"New version available"**:
- **Windows:** click **Update**. The app downloads the installer, checks the VATT Wallet signature and installs it.
- **Android:** tap **Update** and then **Install**. Your wallet is kept.

## ✅ Check that the file is original (optional)

Each version includes the **fingerprint** (SHA-256) of its installers in `SHA256SUMS-windows.txt` and `SHA256SUMS-android.txt`.

On Windows, open **PowerShell** in your downloads folder and type:

```
Get-FileHash .\VATT-Wallet-Setup-X.Y.Z.exe -Algorithm SHA256
```

The result must be **exactly the same** as the number next to the file in `SHA256SUMS-windows.txt`. If it does not match, **do not install it** and let us know.

## 🔒 Security

- Download VATT Wallet **only from this page**. Do not install copies sent by chat, email or social media.
- **VATT Wallet will never ask for your 12 words, your PIN or your keys.** Anyone who asks for them is trying to steal from you.
- Write your 12 words on paper and keep them in a safe place, away from your computer and your phone.

## ⚠️ Important notice (disclaimer)

You are solely and fully responsible for your digital assets. If you lose, forget or share your recovery phrase (12 words), your PIN or your private keys, no one will be able to recover your funds: not VATT Wallet and not anyone else. VATT Wallet is not responsible for losses caused by the loss, theft or disclosure of that information, or for the transactions you sign. Blockchain transactions are irreversible. VATT Wallet does not provide financial, legal or investment advice.
