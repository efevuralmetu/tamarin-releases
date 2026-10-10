# Tamarin — downloads

Installers for [Tamarin](https://tamarinapp.com), a local-first task and
time manager.

**This repository holds release binaries only.** The application source
lives elsewhere and is not published here.

## Download

Get the latest build from the [releases
page](https://github.com/efevuralmetu/tamarin-releases/releases/latest).

| Platform | File | Notes |
|---|---|---|
| Windows 10/11, 64-bit | `Tamarin_x.y.z_x64-setup.exe` | Installer |

Android and iOS are not distributed here yet.

## Why Windows warns you

The installer is not code-signed yet, so Windows SmartScreen shows
"Windows protected your PC" the first time. Choose **More info → Run
anyway**. A signing certificate is planned; until then this warning is
expected and the honest thing to do is say so rather than tell people to
ignore security prompts in general.

## Verifying a download

Each release lists the SHA-256 of its files. On Windows:

```
certutil -hashfile Tamarin_0.1.0_x64-setup.exe SHA256
```

Compare the result with the value in the release notes.
