---
title: Salut
category: Testing
featuredImage: /articles/img/acta-residence.png
date: 2021-02-22T10:44:08.912Z
description: some testing content
author: Remus Ranca
---
<!--StartFragment-->

From an individual Identity user page, use **Send reset password email** to trigger an email to the user, following the [password recovery email template](https://docs.netlify.com/visitor-access/identity/identity-generated-emails/#password-recovery). The `.ConfirmationURL` variable in that email will include your site address with a `recovery_token` appended. The [Netlify Identity widget](https://github.com/netlify/netlify-identity-widget) will handle this link automatically, or you can develop a custom password reset form with [gotrue-js](https://github.com/netlify/gotrue-js).

## <!--EndFragment-->