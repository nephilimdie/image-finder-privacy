# Privacy Policy for Image Finder in Page

  **Effective date:** August 12, 2026
  **Last updated:** August 12, 2026

  Image Finder in Page is a Chrome extension developed by Stefano Bassetto. This Privacy Policy explains what information the extension handles, how it is used, where it is stored, and
  whether it is shared.

  ## 1. Purpose of the extension

  The extension helps users find matching images and visual duplicates within the currently active web page.

  It scans IMG elements, CSS background images, lazy-loaded content, infinite-scroll content, and virtualized lists. Image comparison is performed using perceptual analysis and OpenCV.

  ## 2. Information handled by the extension

  The extension may handle the following information when the user explicitly starts a search:

  - The reference image selected by the user
  - The URL of the active web page
  - Image URLs referenced by the active page
  - Image dimensions and visual characteristics
  - IMG element attributes and CSS background information
  - Links associated with discovered images
  - Search progress, matches, duplicate groups, and result previews
  - The initial page scroll position, temporarily, so it can be restored after scanning
  - Local preferences related to optional development-support reminders

  The extension does not collect names, postal addresses, email addresses, passwords, authentication credentials, financial information, health information, personal communications, or
  precise location data.

  ## 3. How information is used

  Information is used exclusively to:

  - Discover images displayed on the active web page
  - Compare those images with the reference image selected by the user
  - Detect identical or visually similar images
  - Group duplicate images
  - Display search results
  - Navigate to and highlight a selected result
  - Resume or cancel a search
  - Restore the page position after scanning

  The information is not used for advertising, user profiling, credit assessment, lending, or any purpose unrelated to the extension’s image-search functionality.

  ## 4. Local processing and storage

  Image analysis is performed locally in the user’s browser.

  The developer does not operate a server that receives reference images, page content, page URLs, search results, or image comparison data.

  The selected reference image, search state, results, and preferences may be stored locally by Chrome using browser storage technologies such as IndexedDB and localStorage. This storage
  allows searches to continue while the popup is closed and allows relevant state to be restored when the extension is reopened.

  ## 5. Image requests

  To analyze images, the extension may retrieve image files directly from the websites or content delivery networks referenced by the active page.

  These requests are sent to the original image hosts, not to a server operated by the developer. A temporary Referer header rule may be used when required by a website’s anti-hotlinking
  configuration. This temporary rule is restricted to candidate image requests and is removed after the search.

  The reference image selected by the user is not uploaded to the websites being scanned.

  ## 6. Data sharing and sale

  The developer does not sell, rent, license, transfer, or share user data with third parties.

  The extension does not provide user data to advertising networks, analytics services, data brokers, artificial intelligence services, or external image-matching services.

  Candidate image requests are made only to the original hosts referenced by the web page, as necessary to provide the extension’s image-search functionality.

  ## 7. Optional Ko-fi link

  The extension includes an optional link to the developer’s Ko-fi page.

  Ko-fi is opened only after an explicit user click. The extension does not include the active page URL, reference image, search results, or extension identifiers in the Ko-fi link.

  Any information provided directly to Ko-fi is governed by Ko-fi’s own privacy policy and is not received or controlled by the extension.

  Supporting development is voluntary and does not unlock, restrict, or modify any extension functionality.

  ## 8. Remote code

  The extension does not download or execute remotely hosted code.

  All executable JavaScript, OpenCV, and WebAssembly code is included in the extension package. Network requests retrieve only image resources required for user-initiated comparisons.

  ## 9. Data retention and deletion

  Locally stored information may remain in the browser until:

  - The user selects a new reference image
  - The user removes the current reference image
  - Existing search information is replaced by a new search
  - The user clears the extension’s stored data
  - The extension is uninstalled

  Users can delete all locally stored extension information by removing the extension or clearing its storage through Chrome.

  Because the developer does not receive or store this information on external servers, the developer cannot access, recover, or delete it remotely.

  ## 10. Security

  The extension limits processing to information required for its stated purpose.

  It restricts accepted URL schemes, rejects embedded credentials in image URLs, limits image sizes and metadata, validates extension messages, and uses a restrictive Content Security
  Policy.

  Network image requests may use HTTP or HTTPS depending on the address supplied by the website being scanned. No user data is transmitted to a developer-controlled server.

  ## 11. Chrome Web Store Limited Use disclosure

  The use of information received from Chrome APIs complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.

  Information is used only to provide or improve the extension’s user-facing image-search functionality. It is not used for personalized advertising, transferred for unrelated purposes, or
  used to determine creditworthiness or for lending purposes.

  ## 12. Changes to this Privacy Policy

  This Privacy Policy may be updated when the extension’s functionality or data-handling practices change.

  The latest version will always be available at the public URL supplied in the Chrome Web Store listing. The effective date and last updated date will be revised when material changes are
  made.

  ## 13. Contact

  For questions about this Privacy Policy or the extension’s data-handling practices, contact:

  **Stefano Bassetto**
  Email: [stefanobassetto85@gmail.com](mailto:stefanobassetto85@gmail.com)
  Ko-fi: [https://ko-fi.com/stefanobassetto](https://ko-fi.com/stefanobassetto)
