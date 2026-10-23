---
title: Magic Translate Privacy Policy
permalink: /privacy-policy.html
---


# Magic Translate — Privacy Policy

**Last updated:** 22 October 2026
**Applies to:** the Magic Translate Chrome extension (Manifest V3), version 1.0 and later
**Developer:** Stefan Ghiata ("we", "us")

Magic Translate translates text that you type into web page text fields. This
policy explains exactly what the extension processes, where that processing
happens, and what it never does.

## The short version

- **On-device by default.** With the default engine, translation happens inside
  your browser. The developer receives nothing.
- **Off until you enable it.** Magic Translate does nothing on a site until you
  turn it on for that site.
- **Optional server, your choice.** If you configure a LibreTranslate-compatible
  server, text you translate with that engine is sent to that server. There is no
  default remote endpoint.
- **Free, with no analytics, no tracking, no ads and no accounts.** We do not collect, sell or
  rent your data.
- **Sensitive fields are skipped.** Password, payment-card, one-time-code and
  similar fields are not read or translated.

## 1. What the extension processes

When Magic Translate is enabled for a site, it processes:

1. **Text in editable fields.** Text you type into supported `<input>`,
   `<textarea>` and `contenteditable` fields is read so it can be translated.
   Only the new or changed text is sent to the translation engine. Text is held
   in memory while the page is open and is not stored by the extension.
2. **The page hostname.** Used only to apply your per-site on/off rules.
3. **Your settings.** Source and target language, engine choice, per-site rules,
   timing options, and — only if you choose the LibreTranslate engine — the
   server URL and an optional API key. These are stored locally in
   `chrome.storage.local` on your device. They are not synced by us.

Magic Translate does not read, collect or transmit your browsing history,
keystrokes outside supported fields, page contents, or data from sites where you
have not enabled it. It does not use cookies, fingerprinting or advertising
identifiers.

## 2. Where processing happens

### Default: Chrome's built-in on-device Translator

The default engine uses Chrome's built-in Translator API. Translation runs on
your device. The extension does not send the text to the developer or to any
server we operate.

Chrome itself may download a language pack from Google the first time you use a
language pair. That download is performed by Chrome, not by Magic Translate, and
is governed by Google's terms and Chrome's privacy notice. Magic Translate does
not receive the language pack or its contents.

### Optional: a LibreTranslate-compatible server you configure

If you select the LibreTranslate engine and enter a server URL, the text you
translate is sent directly from your browser to that server. We do not operate
that server, cannot see those requests, and do not control its logging or
retention. The server operator's privacy policy applies. Use only a server you
trust, preferably over HTTPS. If the URL field is empty, this engine is inactive.

An API key, if you enter one, is stored locally and sent only to the server you
configured. We never receive it.

## 3. Data sharing and sale

- We do not collect your data, so we have nothing to share or sell.
- We do not sell, rent, trade or transfer personal data to third parties.
- We do not use data for advertising, profiling, creditworthiness or lending.
- The only recipient of translated text is the LibreTranslate server you choose
  yourself.
- There are no analytics SDKs, telemetry, crash reporters, ad networks or
  third-party trackers in the extension. All code is packaged with the extension;
  it does not load or execute remote code.

## 4. Retention

- Typed text is kept in memory only while needed for translation and is
  discarded when the page is closed or the field changes. The extension does not
  write typed text to storage.
- Settings remain in local extension storage until you change them, clear them,
  or uninstall the extension. Uninstalling removes them.
- Retention on a LibreTranslate server is controlled by that server's operator.

## 5. Your controls

- Turn Magic Translate on or off per site from the toolbar popup or with
  `Alt+Shift+T`.
- Disable automatic translation in Options, or uninstall the extension at any
  time.
- Keep everything on-device by leaving the LibreTranslate server URL empty.
- Remove a stored API key by clearing the field in Options.
- Revert a translated segment from the hover/focus bubble while the page is open.

## 6. Children

Magic Translate is a general-purpose writing tool and is not directed to children
under 13. We do not knowingly collect data from anyone, including children.

## 7. Security

- The extension runs no remote code.
- Sensitive fields (passwords, card numbers, one-time codes and similar) are
  detected and skipped before their contents are read.
- Settings, including an optional API key, are stored only in local extension
  storage on your device.
- For the optional LibreTranslate engine, use an HTTPS server. HTTP is permitted
  only because some self-hosted servers run on a local network; traffic over HTTP
  is not encrypted.

## 8. Changes to this policy

If this policy changes, we will update the date above and describe material
changes in the extension's release notes. Continued use after an update means you
accept the revised policy.

## 9. Contact

Questions about this policy or the extension:

The developer of Magic Translate (an independent, non-commercial hobby project)
Email: `magictranslate@proton.me`

A support contact is also available from the Magic Translate Chrome Web Store
listing.

---

*This document is written to be hosted as a public web page (for example GitHub
Pages). It is a product privacy policy, not legal advice.*
