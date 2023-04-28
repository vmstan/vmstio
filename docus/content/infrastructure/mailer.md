---
title: Mailer
description: 'Where do e-mails come from, Dad?'
---

# Mailer

All e-mail notifications associated with the vmst·io Mastodon instance should come from either: `mastodon@sender.vmst.io` or previously `mastodon@mailer.vmst.io`

* We use **[Mailgun](https://mailgun.com)** as our backend service provider for `SMTP`.
* We leverage industry technologies like `SPF` to help verify we are the only ones sending you emails.
* We also use **[EasyDMARC](https://easydmarc.com)** to handle things like `DMARC` and `BIMI` for the domain.
* We use **[Proton](https://proton.me)** for the root `@vmst.io` domain.

## Phishing and Privacy

Our domain policies instruct your email provider to reject any other party that is attempting to use the `@vmst.io` domain to phish you.

When you sign up for an account, and you provide us an email address, we promise to only contact you there regarding your Mastodon account.
For more details, refer to our [Privacy Policy](https://vmst.io/privacy-policy)
