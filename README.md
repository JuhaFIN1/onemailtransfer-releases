<p align="center"><img src="logo.png" alt="One MailTransfer" width="120"></p>

# One MailTransfer – downloads

**Move your email to a new address without losing a single message.**
Free desktop program for Windows, macOS and Linux. No installer, nothing else to install.

**Sähköpostit uuteen osoitteeseen ilman yhtään kadonnutta viestiä.**
Ilmainen työpöytäohjelma Windowsille, macOS:lle ja Linuxille. Ei asennusohjelmaa, ei muita asennettavia osia.

## Download / Lataa

Latest version: **[Releases → latest](../../releases/latest)**

| System | File |
|---|---|
| Windows 10/11 (Intel/AMD) | `OneMailTransfer-<version>-windows-amd64.zip` |
| Windows on ARM | `OneMailTransfer-<version>-windows-arm64.zip` |
| macOS 11+ (Apple silicon and Intel) | `OneMailTransfer-<version>-macos-universal.zip` |
| Linux (x86-64) | `OneMailTransfer-<version>-linux-amd64.tar.gz` |
| Linux (ARM64) | `OneMailTransfer-<version>-linux-arm64.tar.gz` |

`checksums.txt` in each release lists the SHA-256 of every file so you can verify your download.

## Start / Käynnistys

**Windows** – Unzip, double-click `OneMailTransfer.exe`. Your browser opens with the program. If Windows shows
"Windows protected your PC", click *More info* → *Run anyway* (the program is not signed with a paid certificate yet).
*Pura zip, kaksoisnapsauta `OneMailTransfer.exe`. Jos Windows varoittaa, valitse "Lisätietoja" → "Suorita silti".*

**macOS** – Unzip, open `One MailTransfer.app` (drag it to Applications first if you like). The first time: right-click →
*Open* → *Open* (the app is not notarised yet), or run once in Terminal:
`xattr -dr com.apple.quarantine "/Applications/One MailTransfer.app"`.
To read Apple Mail, give the app *Full Disk Access* in System Settings → Privacy & Security.

**Linux** – `tar xzf OneMailTransfer-*.tar.gz && cd OneMailTransfer && ./onemailtransfer`, or `./install.sh` to add it to your
application menu (no root needed).

When you are done, press **Quit / Sulje ohjelma** in the program (top right).

## What it does

* Backup first: all mail is saved on your computer and verified before anything is moved.
* The old mailbox is only read; nothing in it is deleted, moved or marked as read.
* Moves mail from web hosts, Gmail, Microsoft 365, iCloud, Yahoo, Zoho, Fastmail, any IMAP/POP3 server, Apple Mail, Thunderbird,
  Outlook files (.pst, .olm), mbox, eml and Maildir. Up to 100 mailboxes in one run (CSV/Excel import).
* Correct dates and flags, resumes after a power cut or crash without duplicates, adapts its speed to be kind to servers.
* Domain check after the move: DNS and MX, SPF, DKIM, DMARC, reverse DNS, block lists and certificates, with ready fixes.
* English and Finnish.

## Privacy / Yksityisyys

Everything runs on your computer. Mailbox passwords, messages and metadata are sent only to the old and the new mail server
you choose – never to BluexDEV. No telemetry. An optional anonymous version check can be turned off in Settings.

## Terms / Käyttöehdot

Free for the time being. You may not modify, copy or redistribute the program, or present it as your own.
Owner: **BluexDEV Software**. Full terms (English and Finnish): [TERMS.md](TERMS.md).

## Support / Tuki

Open an [issue](../../issues). In the program, *Settings → Export diagnostics* creates a file with logs and no passwords or message contents.

© 2026 BluexDEV Software. All rights reserved.
