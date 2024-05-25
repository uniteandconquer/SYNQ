# SYNQ
### Android App for Qortal
The following are all of the TL/DR 'What's new' bullet points (when available) for all previous SYNQ releases accompanied by a link to each actual release where you can find the detailed release notes.
The releases are in chronological order from the first release up until the latest release.

---

## SYNQ v0.0.1 beta:

SYNQ allows you to view and monitor multiple accounts from your Android device, it is also possible to add accounts to watchlists and setup notifications for accounts on those watchlists. Currently only notifications pertaining to minting activity are available, such as periodically receiving minting reports for one selected account. Notifications for when a mintint account on your watchlist has stalled and when it resumes minting are also offered. 

The app can collect minting data for all added minting accounts with increased minting data collection for accounts on your selected watchlist if you have notifications enabled in the background.

In the future more notifications and actions should become available.

https://github.com/uniteandconquer/SYNQ/releases/tag/SYNQ-v0.0.1

---

## SYNQ v0.0.2 beta

### What's new:

- Improved app start up time and API call responsiveness.
- Modified app navigation flow on start-up, the app will remember if you were logged into a watchlist or not in the previous session and return to either the main screen or watchlist screen the next time you start the app.
- Added an info button to each transaction item in the Transactions screen to show the full transaction details in JSON format.
- Added Qchat (read only) with a lot of extra bells and whistles.
- Chat screen scroll to top and bottom, unread count and 'scroll to unread' count (how far you need to scroll to get to the last unread message).
- Chat groups screen with message info badge informing you of the number of total messages and unread messages for each group.
- Multiple options available on how the chat groups screen behaves (sorting types, auto refresh, etc).
- Two chat screen styles are available. Telegram type style (messages framed in 'chat bubbles') and Discord type style (messages not framed).
- Added QDN gallery where you can view images that were saved in Qchat as public or private images, favorite them, share them and view them in a scrollable an zoomable full screen gallery or in a filterable grid view.
- Saved images are stored locally in the app's folder and can be shared using social (and other) media and saved to your Downloads folder.
- It is possible to select multiple QDN images and export them as a list of references in a JSON file which can be imported to another instance of the app. This JSON file can be considered as a list of instructions of how to fetch those images from QDN.
- Added social (and other) media 'Share' functionality. You can either share account info or invite friends to Qortal and SYNQ with links and a short message.
- Added Find User screen and User Info screen, where you can lookup accounts by name or address and get account info, explore their transactions, share their info and/or Exqlorer link and block users (more actions will be added in the future).
- Added optional connectivity footer to give you direct control throughout the entire app over which node you use to make API calls.
- Improved the Connectivity Menu.

https://github.com/uniteandconquer/SYNQ/releases/SYNQ-v0.0.2

---

## SYNQ v0.0.3 beta

### No TL/DR

https://github.com/uniteandconquer/SYNQ/releases/SYNQ-v0.0.3

---

## SYNQ v0.1.0 beta

### No TL/DR

https://github.com/uniteandconquer/SYNQ/releases/tag/SYNQ-v0.1.0

---

## SYNQ v0.1.1 beta

### No TL/DR

https://github.com/uniteandconquer/SYNQ/releases/tag/SYNQ-v0.1.1

---

## SYNQ v0.1.2 beta

### No TL/DR

https://github.com/uniteandconquer/SYNQ/releases/tag/SYNQ-v0.1.2

---

## SYNQ v0.2.0 beta

### What's new:

* Posting chat messages has been implemented, both for group and private chats. Only available for authenticated accounts with a minimum balance of 4 QORT.
* Super Chats: you can now post a chat with an added donation amount which can be set from within the Editor. Payments are made directly from your account to the recipient's account. No extra fees are charged beyond the standard transaction fee of 0.01 QORT.
* Replies and message editing.
* Auto saving of drafts in the message editor and restoring drafts when returning to the editor.
* Easily clear your entire message with the click of a button.
* Header in the Editor informs you of the type of message you are sending.
* Expandable replied to message in Editor which allows you to quickly view the message you're replying to.
* Updated UI, UX and styling to account for the newly added features.
* Multiple improvements to UI, UX and styling.
* Fixed search by group ID bug in Group Management and added search by owner name.
* Optional prominent styling for Super Chats and replies to the currently selected account.
* Improved styling for replied to messages and replied to messages that have expired or from users whom you've blocked.
* Multiple bug fixes.

https://github.com/uniteandconquer/SYNQ/releases/tag/SYNQ-v0.2.0

---

## SYNQ v0.2.1 beta

### What's new:

- Fixed unreadable text in Editor screen when device is in light mode.
- Added undo/redo feature to the chat Editor.
- Added multiple new context dependent message actions and action icons.
- Message actions are now hidden by default and can be expanded by tapping on the expand icon. This reduces clutter and improves performance.
- Added (multi) image attachments to chat messages. Attach up to 9 images from your QDN gallery to the chat Editor. Multi image support is not yet supported in the Qortal UI, all attached images will be visible in the SYNQ app but only the first attached image will be visible in the Qortal UI. 
- Added filter chat messages by user. When enabled only messages from selected user will be shown.
- Added message forwarding and forwarded message detection. Forwarded messages will now contain a 'Forwarded Message' header.
- Added manual chat history persistence. You can now manually save and load chat messages to and from your device.
- Saved messages will automatically be updated if a message edit is detected.
- An expired replied to message will still be accessible if that message was saved.
- It is now possible to view the replied to messages from blocked users by tapping the replied to message component.
- It is now possible to send a direct private message to someone from their User Info screen.
- SYNQ message suffix when sharing a QDN image to social and other media is now optional.
- Added chat group avatars to Chat Groups screen and Group Management screen. If no group avatar is available, the group owner's user avatar will be used (if available).
- Fixed jumping chat messages bug when scrolling around the 10th message from the bottom of the messages list.
- Improved chat floating buttons and bottom buttons functionality.
- Additional quality of life improvements and bug fixes.

https://github.com/uniteandconquer/SYNQ/releases/tag/SYNQ-v0.2.1

---

## SYNQ version 0.2.2 beta.

This version contains some bug-fixes and some more quality of life additions to the features that were introduced in the previous release.

### What's new?

- Confirm before forwarding message to a chat group.

- Saved messages are now identifiable by an icon.

- Non-expired messages that have been saved can now be deleted.

- Saved messages that have expired are now editable. These messages can be loaded into the Editor screen but will be sent as a new message since editing expired messages is not possible.

- Added 'Load last draft' snack-bar to Editor Screen if the last Editor session was successful (message posted). If unsuccessful the Editor Screen will still display the 'Load draft' modal dialog.

- Modified 'Save' message action to context dependent 'Save' or 'Delete' message action.

- Fixed issue where the 'User header' was not being displayed properly (misaligned avatar and username/address).

- Fixed the issue where replied to messages were not rendered correctly when in selection mode.

- Fixed issue where interactive components were still interactive in selection mode, causing the Image Gallery, User Info screen or Save/Delete dialog to be displayed when tapping on such a component while selecting messages.

- Message selector snack-bar is now a floating snack-bar and will not affect the chat messages list. The selector will be displayed at the top of the list unless the user has scrolled all the way to the top, in which case the snack-bar will be displayed at the bottom.

- Modified all Chat Messages Tab snack-bar styles. This should solve most if not all remaining 'jumpy' chat messages issues.

https://github.com/uniteandconquer/SYNQ/releases/tag/SYNQ-v0.2.2


