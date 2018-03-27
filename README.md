# Firefox-58-multirow-tabs

## Summary
User interface customization for Firefox 58+ in order to display tabs in multiple rows/multiple lines and get rid of the awful lateral scrollbox.

## Install
Go to your `./mozilla/firefox/{your session name}.default/` directory, where `{your session name}` will look something like 8 alphanumeric character (mine is mwad0hks for example)

`git clone https://github.com/krustymars/Firefox-58-multirow-tabs/`

Restart your firefox

You're done :D


## Details
Before Firefox 58, there used to be an awesome extension called Tab Mix Plus that allowed to displays tabs on several lines when there's too much of them opened.
Unfortunately following Firefox update its add-ons system to the new WebExtension format, making Tab Mix Plus unavailable for Firefox 58+.

This repository attempts to workaround the multirow feature unavailability by using a CSS customization file fixing the GUI.
