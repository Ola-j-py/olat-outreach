# Publish Olat Outreach with GitHub Desktop

The repository is prepared to publish only the contents of `/docs` through GitHub Pages.
Internal research, Japanese review pages, CRM files, and email drafts remain outside the Pages source folder.

## One-time GitHub Pages setting

1. Open the `olat-outreach` repository in GitHub Desktop.
2. Review the changes, enter a summary such as `Publish OSEA snapshot`, and click **Commit to main**.
3. Click **Push origin**.
4. On GitHub, open the repository and go to **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch **main** and folder **/docs**, then click **Save**.
7. Wait for the Pages deployment to finish.

## OSEA public URL

https://ola-j-py.github.io/olat-outreach/review/osea-malibu/

## Verification checklist

- Open the URL in a private/incognito window.
- Confirm the OSEA page loads on desktop and mobile.
- Confirm the Japanese page, research notes, CRM, and email drafts are not in `/docs`.
- Paste the verified URL into the Gmail draft and send only after reviewing the recipient and content.

## Privacy note

GitHub Pages is public. `robots.txt` and `noindex` reduce search-engine discovery, but they are not access controls. Publish only public-source, non-confidential content.
