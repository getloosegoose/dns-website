# Understanding DNS

My name is Ben Rios Lopez, and this is my Milestone 1 website for IT 3203 at Kennesaw State University in Fall 2026. My topic is the Domain Name System, or DNS.

I'm interested in networking, Cisco equipment, and IT infrastructure. My goal is to become a network engineer. In this project, I explain what DNS does, how a lookup works, and why DNS security matters.

## What's on my website

- `index.html`: My homepage, with an introduction, key terms, and links to the other pages.
- `dns-basics.html`: How DNS works and what the main record types do.
- `dns-security.html`: Common attacks, DNSSEC, DoH, and DoT.
- `key-concepts.html`: Seven DNS concepts with examples.
- `references.html`: Sources for the DNS information and resources for learning HTML and CSS.
- `about.html`: My education, interests, and goals for this project.

## How to open my website

Extract the ZIP, open the `dns-website` folder, and double-click `index.html`. The pages and diagrams work locally. An Internet connection is needed to open the external reference links.

For a local HTTP preview with Python installed, run this command inside the folder:

```text
python -m http.server 8765 --bind 127.0.0.1
```

Then open http://127.0.0.1:8765. Press Ctrl+C in the terminal when finished.

## How my project is organized

My website uses HTML5 and one shared CSS file called `style.css`. Each HTML file has its own content, with the same navigation menu and footer.

- The `head` includes the page title and the link to the stylesheet.
- The `main` element holds the page's information.
- Headings, paragraphs, lists, images, and tables organize the content.
- The stylesheet uses element, class, and ID selectors.
- Flexbox arranges the menu, homepage introduction, and content cards.
- The `images` folder contains two SVG diagrams with descriptive alt text in the HTML.
- Comments explain the main parts of the HTML and CSS.

My Milestone 1 project does not include the JavaScript quiz for Milestone 2.

## My sources

My references page lists RFC documents, ICANN, and Cloudflare for DNS information. It also includes MDN and a freeCodeCamp video for learning HTML and CSS. Links beside the DNS explanations lead to the relevant entries on my references page.

## Publishing my website

My project repository is `getloosegoose/dns-website`. To publish or update it:

1. Open the repository and choose **Add file → Upload files**.
2. Upload the contents of the project folder. Keep `index.html` at the repository root and the diagrams inside `images`.
3. Commit the changes to `main`.
4. Open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/(root)`, and save.
5. When deployment finishes, open the URL shown by GitHub and check every page.

GitHub's instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Checks and submission

The included test results show that all six pages passed the W3C Nu HTML Checker with no messages. Local checks also passed for the page links, citation anchors, images, and stylesheet. These results are in `TEST-RESULTS.txt` and `validation-results.json`.

My remaining submission steps are:

1. Make sure the latest files are uploaded and GitHub Pages is working.
2. Open every page on the published site and check the links and images.
3. Revalidate any HTML changed after the recorded checks at https://validator.w3.org/.
4. Submit the source ZIP in the D2L Milestone 1 Assignment Dropbox.
5. Put my live website URL directly in the **Comments textbox** as a clickable link.
6. Check D2L for the due date and any additional instructions.

The ZIP includes my six HTML pages, stylesheet, images, and project documentation. Public deployment and D2L submission have not yet been verified. Full mobile, keyboard, and cross-browser testing is still outstanding.
