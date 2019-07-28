![CaseIT logo](readme-img/caseit-logo-black.png)

# Website

HTML, CSS, and [Bootstrap](https://getbootstrap.com/) website for <span style="color:#d32029; font-weight:bold">CaseIT</span>, the premier international Management Information Systems (MIS) business case competition hosted each year in collaboration with the Beedie School of Business in Vancouver, Canada.

The website is hosted with [GitHub pages](https://pages.github.com/) and can be found at https://caseit-sfu.github.io or https://www.caseit.org.

The application form is hosted on [Typeform](https://www.typeform.com/) under a separate account.

## Setup

Open `index.html` in a browser and verify that the website functions properly.

### Troubleshooting

If the header and footer are not displaying and you are using Firefox, the header and footer injection may be blocked by CORS. To diagnose this, right-click on the page, click _Inspect Element_, and navigate to _Console_. If the issue is CORS, the error should be:

```
Cross-Origin Request Blocked: The Same Origin Policy disallows reading the remote resource at file:///path/to/website/caseit.github.io/header.html. (Reason: CORS request not http).
Cross-Origin Request Blocked: The Same Origin Policy disallows reading the remote resource at file:///path/to/website/caseit.github.io/footer.html. (Reason: CORS request not http).
```

To fix this, navigate to `about:config` and set the property `privacy.file_unique_origin` to `false` while working on the website.
