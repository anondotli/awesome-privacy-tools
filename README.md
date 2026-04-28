# Awesome Privacy Tools

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](LICENSE)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

> A curated list of the best privacy tools, open-source privacy tools, encrypted messaging apps, anonymous email services, VPNs, Tor tools, password managers, secure file sharing apps, browser privacy extensions, and self-hosted privacy software.

**Awesome Privacy Tools** helps people find practical tools for private email, encrypted chat, anonymous browsing, password security, data removal, device hardening, and self-hosted alternatives to surveillance-based products.

## Contents

- [Start Here: Best Privacy Tools by Use Case](#start-here-best-privacy-tools-by-use-case)
- [Selection Criteria](#selection-criteria)
- [Anonymous Email Aliases and Private Email](#anonymous-email-aliases-and-private-email)
- [Encrypted Messaging and Secure Chat](#encrypted-messaging-and-secure-chat)
- [Private Browsers and Search Engines](#private-browsers-and-search-engines)
- [Browser Privacy Extensions](#browser-privacy-extensions)
- [VPNs, Tor, and Network Privacy](#vpns-tor-and-network-privacy)
- [DNS, Ad Blocking, and Tracker Blocking](#dns-ad-blocking-and-tracker-blocking)
- [Password Managers, Passkeys, and Authentication](#password-managers-passkeys-and-authentication)
- [File Encryption and Secure File Sharing](#file-encryption-and-secure-file-sharing)
- [Private Cloud Storage, Notes, and Collaboration](#private-cloud-storage-notes-and-collaboration)
- [Operating Systems and Device Privacy](#operating-systems-and-device-privacy)
- [Mobile Privacy Tools](#mobile-privacy-tools)
- [Photo, Metadata, and Media Privacy](#photo-metadata-and-media-privacy)
- [Self-Hosted Privacy Tools](#self-hosted-privacy-tools)
- [Privacy-Friendly Analytics and Developer Tools](#privacy-friendly-analytics-and-developer-tools)
- [Privacy Checkers, Breach Monitoring, and Data Removal](#privacy-checkers-breach-monitoring-and-data-removal)
- [Cryptography and Security Libraries](#cryptography-and-security-libraries)
- [Privacy Guides and Learning Tools](#privacy-guides-and-learning-tools)
- [More Awesome Lists](#more-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

## Start Here: Best Privacy Tools by Use Case

A quick privacy stack for common needs:

| Need | Tools to compare |
| --- | --- |
| Anonymous email aliases | [anon.li Alias](https://anon.li/alias), [SimpleLogin](https://simplelogin.io/), [addy.io](https://addy.io/), [Firefox Relay](https://relay.firefox.com/) |
| Encrypted email | [Proton Mail](https://proton.me/mail), [Tuta](https://tuta.com/), [Mailbox.org](https://mailbox.org/) |
| Secure messaging | [Signal](https://signal.org/), [SimpleX Chat](https://simplex.chat/), [Briar](https://briarproject.org/), [Element](https://element.io/) |
| Private browsing | [Tor Browser](https://www.torproject.org/download/), [Mullvad Browser](https://mullvad.net/en/browser), [LibreWolf](https://librewolf.net/), [Firefox](https://www.mozilla.org/firefox/) |
| Private search | [DuckDuckGo](https://duckduckgo.com/), [Brave Search](https://search.brave.com/), [Startpage](https://www.startpage.com/), [SearXNG](https://github.com/searxng/searxng) |
| Password security | [Bitwarden](https://bitwarden.com/), [KeePassXC](https://keepassxc.org/), [Proton Pass](https://proton.me/pass), [1Password](https://1password.com/) |
| Two-factor authentication | [Aegis Authenticator](https://getaegis.app/), [Ente Auth](https://ente.io/auth/), [2FAS](https://2fas.com/), [YubiKey](https://www.yubico.com/products/) |
| Secure file sharing | [anon.li Drop](https://anon.li/drop), [OnionShare](https://onionshare.org/), [Magic Wormhole](https://magic-wormhole.readthedocs.io/), [Syncthing](https://syncthing.net/) |
| File encryption | [Cryptomator](https://cryptomator.org/), [VeraCrypt](https://www.veracrypt.fr/), [age](https://age-encryption.org/), [Picocrypt](https://github.com/Picocrypt/Picocrypt) |
| Private operating systems | [GrapheneOS](https://grapheneos.org/), [Tails](https://tails.net/), [Qubes OS](https://www.qubes-os.org/), [Whonix](https://www.whonix.org/) |
| Self-hosted privacy | [Nextcloud](https://nextcloud.com/), [Vaultwarden](https://github.com/dani-garcia/vaultwarden), [SearXNG](https://github.com/searxng/searxng), [Pi-hole](https://pi-hole.net/) |

## Selection Criteria

A privacy tool should usually meet most of these criteria:

- It improves privacy, anonymity, anti-tracking, encryption, data minimization, or user control.
- It is useful to real people, teams, developers, journalists, activists, or self-hosters.
- It explains its security model, privacy model, limitations, or trust assumptions.
- It is actively maintained, widely used, independently reviewed, or historically important.
- It avoids deceptive privacy claims, dark patterns, surveillance advertising, and unnecessary telemetry.
- Open source is preferred, but strong closed-source tools may be included when the trust model and track record are clear.

No affiliate links. No paid placement. No fake “best” rankings.

## Anonymous Email Aliases and Private Email

- [anon.li Alias](https://anon.li/alias) - Private email aliases with forwarding, reply-by-alias, PGP forwarding, and custom domains.
- [addy.io](https://addy.io/) - Open-source anonymous email forwarding and aliasing.
- [DuckDuckGo Email Protection](https://duckduckgo.com/email/) - Email forwarding service that removes common trackers.
- [Firefox Relay](https://relay.firefox.com/) - Email masks from Mozilla for hiding your real address.
- [Forward Email](https://forwardemail.net/) - Open-source email forwarding service with custom domain support.
- [Mailfence](https://mailfence.com/) - Private email, calendar, contacts, and document service with OpenPGP support.
- [Mailbox.org](https://mailbox.org/) - Privacy-oriented email and office suite.
- [Mailvelope](https://mailvelope.com/) - Browser extension for OpenPGP email encryption.
- [Proton Mail](https://proton.me/mail) - Encrypted email service with web, desktop, and mobile apps.
- [SimpleLogin](https://simplelogin.io/) - Open-source email alias service for shielding your real email address.
- [Thexyz](https://www.thexyz.com) - Email hosting service with custom domains, spam filtering, and privacy-focused mailbox management.
- [Tuta](https://tuta.com/) - Encrypted email, calendar, and contacts service.

## Anonymous Phone Number Aliases

Receive SMS verification codes without exposing your real phone number — the phone-side counterpart to email aliases above. Useful for signups, 2FA, and account recovery on services that require a phone number.

- [VerifySMS](https://verifysms.app) — Pay-per-use virtual numbers in 200+ countries / 500+ services. REST API, iOS/Android/web clients. Automatic refund within 20 minutes if SMS does not arrive. Email-only signup, no KYC under \$250. 5.0 stars across 21 App Store reviews (US: 9, GB: 2, TR: 5, DE: 5). [Privacy Policy](https://verifysms.app/privacy).
- [5SIM](https://5sim.net) — Long-running provider with REST API, mix of real and virtual numbers across multiple countries.
- [SMS-Activate](https://sms-activate.io) — Large catalog of services and countries, REST API, pay-per-use.
- [SMSPool](https://www.smspool.net) — Marketplace model, REST API, multiple countries.

## Encrypted Messaging and Secure Chat

- [Briar](https://briarproject.org/) - Peer-to-peer messaging designed for censorship resistance and offline scenarios.
- [Element](https://element.io/) - Matrix client for end-to-end encrypted personal and team chat.
- [Jami](https://jami.net/) - Peer-to-peer voice, video, and messaging app.
- [Matrix](https://matrix.org/) - Open protocol for decentralized, end-to-end encrypted communication.
- [Molly](https://molly.im/) - Hardened Android client based on Signal.
- [Session](https://getsession.org/) - Metadata-resistant messenger using an onion-routed network.
- [Signal](https://signal.org/) - End-to-end encrypted messenger with strong defaults and broad adoption.
- [SimpleX Chat](https://simplex.chat/) - Private messenger designed without user identifiers.
- [Threema](https://threema.ch/) - Paid encrypted messenger that does not require a phone number.
- [Wire](https://wire.com/) - End-to-end encrypted messaging and collaboration for individuals and teams.

## Private Browsers and Search Engines

- [Brave](https://brave.com/) - Chromium-based browser with built-in tracker blocking and privacy features.
- [Brave Search](https://search.brave.com/) - Search engine with an independent index and privacy-focused defaults.
- [DuckDuckGo](https://duckduckgo.com/) - Private search engine with tracker-blocking browser apps.
- [Firefox](https://www.mozilla.org/firefox/) - Open-source browser with strong extension support and privacy controls.
- [Kagi](https://kagi.com/) - Paid search engine with personalization controls and no ad-funded model.
- [LibreWolf](https://librewolf.net/) - Firefox fork focused on privacy and security defaults.
- [Mullvad Browser](https://mullvad.net/en/browser) - Anti-fingerprinting browser built with the Tor Project and usable without Tor.
- [SearXNG](https://github.com/searxng/searxng) - Self-hostable metasearch engine.
- [Startpage](https://www.startpage.com/) - Private search engine with proxied search results.
- [Tor Browser](https://www.torproject.org/download/) - Browser configured to use Tor and reduce fingerprinting.
- [Whoogle](https://github.com/benbusby/whoogle-search) - Self-hosted private metasearch proxy.

## Browser Privacy Extensions

- [CanvasBlocker](https://github.com/kkapsner/CanvasBlocker/) - Helps resist browser fingerprinting techniques.
- [ClearURLs](https://github.com/ClearURLs/Addon) - Removes tracking parameters from URLs.
- [Cookie AutoDelete](https://github.com/Cookie-AutoDelete/Cookie-AutoDelete) - Deletes cookies from closed tabs with configurable rules.
- [Firefox Multi-Account Containers](https://support.mozilla.org/en-US/kb/containers) - Isolates accounts and browsing contexts in Firefox.
- [LocalCDN](https://www.localcdn.org/) - Emulates common content delivery networks locally.
- [NoScript](https://noscript.net/) - Fine-grained script blocking for advanced users.
- [Privacy Badger](https://privacybadger.org/) - Tracker blocker from the Electronic Frontier Foundation.
- [uBlock Origin](https://github.com/gorhill/uBlock) - Efficient wide-spectrum content blocker.

## VPNs, Tor, and Network Privacy

- [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) - Flexible DNS proxy supporting encrypted DNS protocols.
- [I2P](https://geti2p.net/) - Anonymous overlay network for peer-to-peer services.
- [IVPN](https://www.ivpn.net/) - VPN provider with privacy-oriented policies and clients.
- [Lokinet](https://lokinet.org/) - Onion-routed network for private browsing and service access.
- [Mullvad VPN](https://mullvad.net/) - Privacy-focused VPN with anonymous account numbers and cash payment support.
- [Nym](https://nym.com/) - Mixnet infrastructure for network-level privacy.
- [OnionShare](https://onionshare.org/) - Share files and host temporary sites through Tor onion services.
- [Orbot](https://orbot.app/) - Tor proxy for Android.
- [Proton VPN](https://protonvpn.com/) - VPN service from Proton with open-source apps.
- [Snowflake](https://snowflake.torproject.org/) - Tor pluggable transport that helps people bypass censorship.
- [Tor Project](https://www.torproject.org/) - Onion-routing network for stronger anonymity.
- [WireGuard](https://www.wireguard.com/) - Modern VPN protocol and software.

## DNS, Ad Blocking, and Tracker Blocking

- [AdGuard DNS](https://adguard-dns.io/) - DNS resolver with ad and tracker blocking options.
- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) - Self-hosted network-wide ad and tracker blocker.
- [Control D](https://controld.com/) - Configurable DNS filtering and encrypted DNS resolver.
- [Mullvad DNS](https://mullvad.net/en/help/dns-over-https-and-dns-over-tls) - Public encrypted DNS with optional blocking profiles.
- [NextDNS](https://nextdns.io/) - Configurable DNS filtering and analytics controls.
- [Pi-hole](https://pi-hole.net/) - Network-wide DNS sinkhole for ads and trackers.
- [Quad9](https://www.quad9.net/) - Security-focused recursive DNS resolver.
- [RethinkDNS](https://rethinkdns.com/) - DNS, firewall, and anti-censorship app for Android.
- [Technitium DNS Server](https://technitium.com/dns/) - Self-hosted DNS server with blocking and encrypted DNS support.

## Password Managers, Passkeys, and Authentication

- [1Password](https://1password.com/) - Password manager with passkey support and strong usability.
- [2FAS](https://2fas.com/) - Two-factor authentication app with browser extension support.
- [Aegis Authenticator](https://getaegis.app/) - Encrypted 2FA token manager for Android.
- [Bitwarden](https://bitwarden.com/) - Open-source password manager with hosted and self-hosted options.
- [Ente Auth](https://ente.io/auth/) - Open-source, end-to-end encrypted 2FA app.
- [KeePassDX](https://www.keepassdx.com/) - Android client compatible with KeePass databases.
- [KeePassXC](https://keepassxc.org/) - Offline password manager for desktop.
- [Nitrokey](https://www.nitrokey.com/) - Open hardware security keys and encrypted storage devices.
- [OnlyKey](https://onlykey.io/) - Hardware password manager and security key.
- [pass](https://www.passwordstore.org/) - Unix password manager using GnuPG and Git.
- [Proton Pass](https://proton.me/pass) - Password manager from Proton.
- [SoloKeys](https://solokeys.com/) - Open-source FIDO security keys.
- [YubiKey](https://www.yubico.com/products/) - Hardware security keys for phishing-resistant authentication.

## File Encryption and Secure File Sharing

- [anon.li Drop](https://anon.li/drop) - End-to-end encrypted file sharing with browser-side encryption, expiry, password protection, and download limits.
- [Cryptomator](https://cryptomator.org/) - Client-side encryption for cloud storage.
- [gocryptfs](https://github.com/rfjakob/gocryptfs) - Encrypted overlay filesystem for Linux and macOS.
- [Magic Wormhole](https://magic-wormhole.readthedocs.io/) - Securely transfer files and text between computers.
- [OnionShare](https://onionshare.org/) - Private file sharing through Tor onion services.
- [Picocrypt](https://github.com/Picocrypt/Picocrypt) - Small file encryption tool designed for simplicity.
- [rclone crypt](https://rclone.org/crypt/) - Encrypted remote storage layer for rclone.
- [Syncthing](https://syncthing.net/) - Continuous peer-to-peer file synchronization.
- [VeraCrypt](https://www.veracrypt.fr/) - Disk and container encryption software.

## Private Cloud Storage, Notes, and Collaboration

- [Anytype](https://anytype.io/) - Local-first, end-to-end encrypted workspace for notes and knowledge management.
- [CryptPad](https://cryptpad.org/) - End-to-end encrypted collaborative office suite.
- [Ente Photos](https://ente.io/) - End-to-end encrypted photo storage and sharing.
- [Filen](https://filen.io/) - End-to-end encrypted cloud storage.
- [Joplin](https://joplinapp.org/) - Open-source notes app with optional end-to-end encryption.
- [Nextcloud](https://nextcloud.com/) - Self-hostable file sync and collaboration platform.
- [Notesnook](https://notesnook.com/) - End-to-end encrypted note-taking app.
- [Proton Drive](https://proton.me/drive) - Encrypted cloud storage from Proton.
- [Standard Notes](https://standardnotes.com/) - Encrypted notes app with cross-platform sync.
- [Tresorit](https://tresorit.com/) - End-to-end encrypted cloud storage and collaboration.

## Operating Systems and Device Privacy

- [CalyxOS](https://calyxos.org/) - Android-based mobile OS with privacy-respecting defaults.
- [GrapheneOS](https://grapheneos.org/) - Hardened mobile OS for Pixel devices.
- [Kicksecure](https://www.kicksecure.com/) - Security-hardened Linux distribution from the Whonix project.
- [Qubes OS](https://www.qubes-os.org/) - Security-focused desktop OS using compartmentalization.
- [Secureblue](https://github.com/secureblue/secureblue) - Hardened Fedora Atomic images with security-focused defaults.
- [Tails](https://tails.net/) - Amnesic live operating system that routes traffic through Tor.
- [Whonix](https://www.whonix.org/) - Desktop OS designed for Tor-based anonymity.

## Mobile Privacy Tools

- [App Manager](https://github.com/MuntashirAkon/AppManager) - Android app manager with privacy and permission controls.
- [Aurora Store](https://auroraoss.com/) - Alternative Google Play client.
- [Exodus Privacy](https://exodus-privacy.eu.org/) - Android app tracker and permission reports.
- [F-Droid](https://f-droid.org/) - Catalog of free and open-source Android apps.
- [NetGuard](https://github.com/M66B/NetGuard) - No-root firewall for Android.
- [Obtainium](https://github.com/ImranR98/Obtainium) - Install and update Android apps directly from release sources.
- [Orbot](https://orbot.app/) - Tor proxy for Android.
- [RethinkDNS](https://rethinkdns.com/) - DNS, firewall, and anti-censorship app for Android.
- [Shelter](https://gitea.angry.im/PeterCxy/Shelter) - Android work-profile isolation tool.
- [TrackerControl](https://trackercontrol.org/) - Android app for monitoring and blocking tracking.

## Photo, Metadata, and Media Privacy

- [ExifEraser](https://github.com/Tommy-Geenexus/exif-eraser) - Android app for removing image metadata.
- [ExifTool](https://exiftool.org/) - Read, write, and remove metadata from media files.
- [ImageOptim](https://imageoptim.com/mac) - Image optimizer for macOS that can remove metadata.
- [Immich](https://immich.app/) - Self-hosted photo and video backup solution.
- [MAT2](https://0xacab.org/jvoisin/mat2) - Metadata anonymization toolkit.
- [Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif) - Android app for removing EXIF metadata before sharing images.

## Self-Hosted Privacy Tools

- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) - Self-hosted ad and tracker blocking DNS server.
- [Authentik](https://goauthentik.io/) - Self-hosted identity provider for single sign-on.
- [Authelia](https://www.authelia.com/) - Self-hosted authentication and authorization server.
- [FreshRSS](https://freshrss.org/) - Self-hosted RSS reader that reduces dependence on algorithmic feeds.
- [Headscale](https://github.com/juanfont/headscale) - Open-source coordination server for Tailscale-compatible networks.
- [Home Assistant](https://www.home-assistant.io/) - Local-first home automation platform.
- [Mailcow](https://mailcow.email/) - Self-hosted mail server suite.
- [Nextcloud](https://nextcloud.com/) - Self-hosted file sync, calendar, contacts, and collaboration platform.
- [Pi-hole](https://pi-hole.net/) - Network-wide DNS sinkhole for ads and trackers.
- [SearXNG](https://github.com/searxng/searxng) - Self-hosted private metasearch engine.
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - Lightweight self-hosted Bitwarden-compatible server.
- [Whoogle](https://github.com/benbusby/whoogle-search) - Self-hosted private search proxy.

## Privacy-Friendly Analytics and Developer Tools

- [Fathom Analytics](https://usefathom.com/) - Privacy-focused website analytics without invasive tracking.
- [GoatCounter](https://www.goatcounter.com/) - Open-source, privacy-friendly web analytics.
- [Matomo](https://matomo.org/) - Open-source analytics platform with privacy controls.
- [Plausible](https://plausible.io/) - Lightweight, open-source website analytics.
- [PostHog](https://posthog.com/) - Product analytics suite with self-hosting support.
- [Swetrix](https://swetrix.com/) - Privacy-focused analytics and monitoring platform.
- [Umami](https://umami.is/) - Simple, open-source, privacy-focused web analytics.

## Privacy Checkers, Breach Monitoring, and Data Removal

- [BrowserLeaks](https://browserleaks.com/) - Browser privacy and fingerprinting test suite.
- [Cover Your Tracks](https://coveryourtracks.eff.org/) - EFF browser tracking and fingerprinting test.
- [DeleteMe](https://joindeleteme.com/) - Paid service for removing personal data from data broker sites.
- [DuckDuckGo App Tracking Protection](https://duckduckgo.com/app-tracking-protection) - Android tracker blocking built into DuckDuckGo's browser app.
- [Have I Been Pwned](https://haveibeenpwned.com/) - Check whether an email address appears in known breaches.
- [Incogni](https://incogni.com/) - Paid data broker removal service.
- [JustDeleteMe](https://justdeleteme.xyz/) - Directory of account deletion links and difficulty ratings.
- [Mozilla Monitor](https://monitor.mozilla.org/) - Breach alerts and exposure guidance from Mozilla.
- [Simple Opt Out](https://simpleoptout.com/) - Directory of opt-out links for data sharing and marketing programs.
- [Terms of Service; Didn't Read](https://tosdr.org/) - Summaries and ratings for online terms and privacy policies.

## Cryptography and Security Libraries

- [age](https://age-encryption.org/) - File encryption format and CLI with a small, auditable design.
- [GnuPG](https://gnupg.org/) - Complete implementation of OpenPGP.
- [libsodium](https://doc.libsodium.org/) - Modern, easy-to-use cryptography library.
- [OpenMLS](https://openmls.tech/) - Rust implementation of Messaging Layer Security.
- [OpenPGP.js](https://openpgpjs.org/) - JavaScript implementation of the OpenPGP protocol.
- [Sequoia PGP](https://sequoia-pgp.org/) - Modern OpenPGP implementation in Rust.
- [Sigstore](https://www.sigstore.dev/) - Signing and transparency tooling for software supply chains.
- [sops](https://github.com/getsops/sops) - Editor for encrypted secrets files.
- [The Update Framework](https://theupdateframework.io/) - Framework for securing software update systems.
- [TruffleHog](https://github.com/trufflesecurity/trufflehog) - Secret scanning tool for repositories and other sources.

## Privacy Guides and Learning Tools

- [Data Detox Kit](https://datadetoxkit.org/) - Step-by-step privacy exercises for everyday users.
- [Digital Defense Fund Guides](https://digitaldefensefund.org/ddf-guides/) - Security and privacy guides for reproductive rights and advocacy contexts.
- [Electronic Frontier Foundation](https://www.eff.org/) - Digital rights organization covering privacy, free expression, and surveillance.
- [Mozilla Privacy Not Included](https://foundation.mozilla.org/en/privacynotincluded/) - Consumer privacy reviews for connected products and apps.
- [OWASP Top 10 Privacy Risks](https://owasp.org/www-project-top-10-privacy-risks/) - Privacy risk model for software teams.
- [Privacy Guides](https://www.privacyguides.org/) - Independent knowledge base for privacy and security tools.
- [Security Planner](https://securityplanner.consumerreports.org/) - Personalized security and privacy recommendations.
- [Surveillance Self-Defense](https://ssd.eff.org/) - EFF guide for safer communication, devices, and accounts.
- [Threat Modeling Manifesto](https://www.threatmodelingmanifesto.org/) - Principles for identifying and reducing security risks.

## More Awesome Lists

- [awesome](https://github.com/sindresorhus/awesome) - The canonical list of awesome lists.
- [Awesome Cryptography](https://github.com/sobolevn/awesome-cryptography) - Cryptography resources and libraries.
- [Awesome Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) - Security learning resources.
- [Awesome Humane Tech](https://github.com/humanetech-community/awesome-humane-tech) - Humane, ethical, and privacy-conscious technology.
- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - Self-hosted software and services.
- [Awesome Security](https://github.com/sbilly/awesome-security) - Software security resources.
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - Open-source sysadmin resources.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

Good contributions add high-quality privacy tools, improve descriptions, remove dead links, disclose conflicts of interest, and keep the list neutral.

## License

[CC0 1.0 Universal](LICENSE). Public domain dedication.
