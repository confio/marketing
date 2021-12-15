# Instructions for setting up a custom Confio signature

1. Copy the contents of signature.html.
2. Go to [CodePen](https://codepen.io/pen/?editors=1000) and paste the contents in the top HTML box.
3. Find the following data on the HTML and replace its default values with your data (do not replace the data-tags themselves):
  - `data-name`: Your name (default is John Doe)
  - `data-job`: Your job role (default is Job Role)
  - `data-mail-link`'s href: "mailto:[your-email-address]" (default is "mailto:mail@confio.tech")
  - `data-mail`: Your email address (default is mail@confio.tech)
  - `data-linkedin`'s href: Your LinkedIn profile address (default is "https://www.linkedin.com/company/confio-tech")
  - `data-twitter`'s href: Your Twitter profile address (default is "https://twitter.com/confio_tech")
  - `data-medium`'s href: Your Medium profile address (default is "https://medium.com/confio")
  - `data-github`'s href: Your GitHub profile address (default is "https://github.com/confio")

4. If you don't want to share all 4 social networks, you can omit any of them by removing the whole <a> tag of the corresponding data-[social-network]. If you remove LinkedIn, you need to remove the `margin-left:10px;` style from the next social link.
5. Copy the signature that has generated below.
6. Paste it in your signature configuration field of your email provider.
