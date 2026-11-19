# A Beginner's Guide to Understanding URLs (Web Addresses)
Everytime you tap a link or type a website name into your browser, you are using a **URL**. Understanding how a URLs works helps you navigate the web safely,share specific files accurately, and troubleshoot broken links.
## What is a URL?
**URL** stands for **Uniform Resources Locator**. In plain English, it is the unique web address of a specific page, document, image, or video on the internet.
Think of a URL like a **physical house address**:
* Just as a postal worker needs a country, street name, and house number to deliver a letter to the right door, your web browser needs a complete URL to locate and display a specific file stored on a remote computer (server).

  ---

  ## Anatomy of a URL
  To see how a web address works, break down this example of a GitHub file link:
  
  `https://www.github.com/samples/understanding-urls.md`
  |Part | Examples | What it Does |
  |:--- | :--- | :--- |
  | **Protocol (Scheme)** | `https://` | Tells your browser *how* to connect to the website and whether the connection is encrypted. |
  | **Subdomain** | `www.` | Sperates a specific section of a large website (for example, `mail.google.com` or `drive.google.com`). |
  | **Domain Name** | `github` | Identifies the unique name of the organizations or website server you are visiting. |
  | **Top Level Domain (TLD)** | `.com` | Indicates the website's categories or country (such as `.com` for commercial, `.org` for organiziation, or `.ng` for Nigeria). |
  | **Path & File Name** | `/sample/understanding-urls.md` | Acts like a hallway and room number, pointing directly to a specific folder and file on that server. |

  ---

  ## Why `https://` Matters for Online Safety
  When inspecting any URL, always check the first five letters before the `://`:
  * **`https://` (Secure):** The **S** stands for **Secure**. Data sent between your smartphone and website is encrypted, protecting your password and personal information from hackers.
  * **`http://` (Not Secure):** Data is sent in plain text without encryption. Avoid entering passwords, bank details, or private information on any page starting with `http://`.

  ---

  ## Quick Checklist Before Sharing a URL
  1. **Verify the exact page:** Ensure you copied the link from the specific file or article page-not the website's main homepage.
  2. **Check for typos:** Changing even one letter or slash (`/`) in the path will lead to a `404 Page not Found` error.
  3. **Confirm security:** look for `https://` at the start of the link before sharing it to others.
