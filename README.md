# Privacy-policy
Privacy Policy — NoCookies (Auto Cookie Decliner)

Last updated: July 2026

## Summary

NoCookies does not collect, store, transmit, or sell any personal data, browsing history, or user information to any external server. Everything the extension does happens locally, inside your own browser.

## What the extension does

NoCookies automatically detects and responds to cookie consent banners on websites you visit, so you don't have to manually click through them. It does this by:

- Recognizing known cookie consent platforms and clicking their "Reject"/"Decline" options on your behalf
- Reading the visible text of banner-like elements on the page to find similar options on custom-built banners
- Sending the Global Privacy Control (GPC) signal, a standard browser opt-out signal, on your behalf
- Optionally, accepting a banner instead if you've turned on the "auto-accept when no reject option exists" setting

## What data this involves, and where it stays

To do the above, the extension needs broad permission to read and interact with the content of the pages you visit (this is why it requests access to all websites). This access is used exclusively to detect and respond to cookie banners in real time, in your own browser.

- **No browsing history is recorded or transmitted.** The extension does not log which sites you visit.
- **No banner content is sent anywhere.** Any analysis of a page's text (to detect a cookie banner) happens locally and is discarded immediately after the decision is made.
- **Local counts only.** The extension keeps a simple count of how many banners it has declined, stored only in your own browser's local storage (chrome.storage.local), never transmitted anywhere. This is used only to show you a number in the extension's popup.
- The "report a cookie warning" feature, if you use it, saves the hostname and a snippet of the relevant page element locally in your own browser, for your own reference — this is not sent to any server, and no one other than you can see it.
- **No account, sign-in, or personal identifiers** are required or collected at any point.
- **No advertising, analytics, or tracking SDKs** are included in this extension.

## Third parties

This extension does not share any data with third parties, because it does not collect any data to share. The optional donation link shown occasionally in the popup takes you to a separate, external Ko-fi page if you choose to click it — Ko-fi's own privacy policy applies to that separate site, not to this extension.

## Changes to this policy

If this policy is updated, the "Last updated" date above will be revised accordingly.

## Contact

Questions about this policy can be directed to fission.studio1@gmail.com.
