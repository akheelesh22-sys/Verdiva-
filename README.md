# Verdiva Ltd storefront

A responsive, mobile-first static storefront for Verdiva Ltd. The app is built as a single HTML file and does not require a build step or package installation.

## Run locally

Open `index.html` in a browser. Basket selections are saved in that browser using local storage.

## Publish with GitHub Pages

1. Create a GitHub repository and add `index.html` to its root.
2. Push the files to the repository's default branch.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the default branch and the `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site; the Pages screen will show its URL.

## WhatsApp checkout

Checkout prepares the complete order receipt and opens WhatsApp addressed to Verdiva at **+230 5845 4925**. The customer must review and tap **Send** in WhatsApp. A `wa.me` link cannot send a message without that customer action. Fully automatic sending requires a server connected to the WhatsApp Business Platform API and its credentials; keep those credentials on the server, never in this static page.

## Notes

- The storefront uses Google Fonts and Unsplash images, so those remote assets need an internet connection to load.
- Basket configuration and order details stay in the customer's browser until the customer sends the WhatsApp message. This static version does not save orders to a business database.
