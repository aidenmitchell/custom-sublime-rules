# custom-sublime-rules

This repo is a collection of [Sublime Security](https://github.com/sublime-security/sublime-platform) rules that I've developed personally.
Most, if not all of these, have been created as a result of emails I've seen in my enviroment that I'd like a rule for.

Rules in development may have a high false positive or false negative rate. Rules in production should be safe.

Please feel free to contribute to this repo, or test these rules in your environment.
I don't have a lot of emails to work with, so testing these rules on larger datasets is much appreciated.

# Rule inventory

| Rule Name                                             | In Development  | In Production | Pushed to Sublime repo | Comments  |
|------------------------------------------------------ |------------ |----------------------------- |---------- | ---------- |
| Brand impersonation: M365 Mail Notifications | ✅ | | | Needs to be tested on a larger dataset; improve detection |
| Brand impersonation: Canada Post | ✅ | | | False positives unlikely |
