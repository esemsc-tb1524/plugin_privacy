# Privacy Policy for Cékikalemédia

**Effective date:** October 4, 2026

Cékikalemédia (the “Extension”) displays information about the ownership of supported media websites.

## Data the Extension accesses

To determine whether information should be displayed, the Extension reads the hostname of the webpage currently open in the browser (for example, `example.com`). Matching takes place locally on the user's device.

The Extension does not read or collect page contents, browsing history, search queries, form entries, cookies, account credentials, personal communications, precise location, or financial, health, or authentication information.

## Data stored on the user's device

The Extension uses Chrome's local extension storage to save:

- whether the Extension is enabled;
- a cache of public website-ownership records downloaded by the Extension;
- the data source and time of the latest refresh; and
- operational status or error messages.

This information remains in the user's browser profile and is not used to identify or track the user. It can be removed by uninstalling the Extension or clearing the Extension's stored data through the browser.

## Network requests and data sharing

When the Extension is enabled or the user requests a data refresh, it connects to a fixed Supabase project to download the public website-ownership dataset. These requests do not include the URL or hostname of the page being viewed, page contents, or other browsing activity.

Like any network service, Supabase and the network infrastructure involved in delivering the dataset may automatically receive standard technical request information, such as the user's IP address, user agent, request time, and diagnostic logs. This information is handled by Supabase under its own privacy terms and is not used by the Extension publisher to track browsing activity.

The Extension does not sell personal information. It does not transfer user data to third parties for advertising, profiling, credit decisions, or other purposes unrelated to the Extension's single purpose.

## Permissions

The Extension uses:

- **Storage permission** to save the local settings, public dataset cache, refresh time, and operational status described above.
- **Access to HTTP and HTTPS webpages** to read the current hostname and display the informational banner on matching websites. Matching is performed locally.
- **Optional access to the configured Supabase project** solely to download the public website-ownership dataset.

The Extension does not request access to browser history, cookies, downloads, or browsing-data APIs.

## Data retention and security

The Extension publisher does not maintain a user database for the Extension. Locally stored settings and cached records remain until they are replaced, cleared by the user, or removed when the Extension is uninstalled. Dataset requests use HTTPS.

## Children's privacy

The Extension is not directed to children and does not knowingly collect personal information from children.

## Changes to this policy

This policy may be updated if the Extension's functionality or data practices change. The effective date above will be revised when material changes are made.

## Contact

Publisher: Tim Bo 
Privacy contact: tboudot2@gmail.com

