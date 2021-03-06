# Documentation

Hey there!
Do you want to have ADN-based support?
Just sign in and create a page.

## Integration

If you're making a client for App.net, you can integrate sending feedback into your app.

This is easy:

- look up your page's post id -- click "Edit" and you'll see it
- add a feedback dialog to your app:
- it should contain a type selector and a text field
- it should publish posts with:
  - `reply_to`: your page's post id
  - `text` starting with your @username, like a regular reply
  - an annotation of type `com.floatboth.supportadn.entry`, value `{"type": "ideas|bugs|praise"}`

NOTE: the type is plural. Yes, this looks weird. No, I'm not going to change it.

## Privacy Policy

SupportApp does not store any private data.
The few pieces of data that are stored in our database are publicly available through the App.net API.

## Terms of Service

SupportApp is a client for App.net, so [App.net terms](https://account.app.net/legal/terms/) apply.
