Privacy Policy – AdminTool for SharePoint
Last updated: [DATUM]

1. Who we are
This privacy policy describes how the browser extension "AdminTool for SharePoint"
("the extension") handles data. The extension is provided by [NAME / FIRMA]
("we", "us"). Contact: [E-MAIL].

2. What the extension does
The extension adds an on-page admin toolset to Microsoft SharePoint Online. It lets
the signed-in user copy and migrate SharePoint pages, remap content types and
metadata, inspect page/search metadata, manage common site-administration tasks, and
quickly navigate via a keyboard overlay (Alt+Q). All actions are performed on the
user's behalf using their existing SharePoint sign-in (session cookies) and the
SharePoint REST API.

3. Data we process
The extension processes the following data, only to perform the actions the user
explicitly requests:
- SharePoint content and metadata of the sites the user works with. This can include
  personally identifiable information that already exists in SharePoint (for example
  author/editor display names and email addresses) and page identifiers such as
  SharePoint page URLs and titles.
- Quicklinks: a small list of navigation links (label + URL) that the user defines.

We do NOT collect analytics, telemetry, browsing behaviour, clicks, keystrokes,
location, passwords or payment data. We do not use tracking, advertising, or
profiling, and we do not sell or rent any data.

4. Where data is processed and stored
- Same-tenant operations run directly between the user's browser and Microsoft
  SharePoint. No content is sent to us.
- Cross-tenant operations (optional) are routed through a relay service operated by
  us (Microsoft Azure Functions) solely to forward the user's request to the target
  SharePoint tenant and return the result. The relay processes the request transiently
  to fulfil the operation and does not persist SharePoint content beyond what is
  required to complete the request. [Falls deine Azure Function Request-Inhalte
  protokolliert/speichert: HIER offenlegen, z. B. "Server logs may retain request
  metadata for X days for troubleshooting."]
- Quicklinks are stored using the browser's own synchronized storage
  (chrome.storage.sync), i.e. within the user's Microsoft/browser account. We have no
  access to this storage.

5. Authentication
The extension relies on the user's existing SharePoint session. It does not collect,
store, or transmit usernames, passwords, or other credentials.

6. Permissions
- "storage": to save the user's personal Quicklinks list.
- Host access to https://*.sharepoint.com/*: required because the extension only
  operates on SharePoint Online and acts across the user's SharePoint sites/tenants.

7. Data retention
We do not maintain a database of user content. Quicklinks remain in the user's own
browser storage until the user changes or removes them. [Relay-Logs: siehe Punkt 4.]

8. Data sharing
We do not share data with third parties. The only external processing is the optional
relay described in section 4, hosted on Microsoft Azure.

9. Children
The extension is intended for business/administrative use and is not directed at
children.

10. Changes
We may update this policy. Material changes will be reflected on this page with an
updated "Last updated" date.

11. Contact
For questions about this policy or your data, contact: [E-MAIL].
