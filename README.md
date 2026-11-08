MsgLedger 2.23.0 — SMS Organisation, Spending Insights & Live Usage Counter

Designed and developed by Abhiram K Suryaprakash, MsgLedger brings readable messaging, automatic SMS organisation and personal spending management together in one Android app.

The app is under active development. Feedback, bug reports and suggestions are welcome.

What’s new in this release

Usage reporting is now enabled by default for installations without a saved preference. Users can turn it off in About or Settings. Previously saved off choices remain respected.

The live counter in About displays active reporting installations over the last 30 days, refreshing approximately once a minute.

Messaging and organisation
- Works as your Android default SMS app to receive, read and send messages.
- Opens to Transactions by default, with an option to open All messages instead.
- Main folders include Transactions, Promotions and Personal, with additional views available through the folder dropdown.
- Uses sender headers, the bundled historical TRAI registry and message content to organise SMS.
- Combines service (-S), transactional (-T) and government (-G) messages into the Transactions view. Promotional (-P) messages go to Promotions.
- Numeric senders shorter than 10 digits, or beginning with 57 or 59, are treated as transactional senders.
- Supports message search, unread filtering and marking all messages as read.
- Shows saved contact names when Contacts access is allowed.
- Refreshes the inbox in the background without startup sync banners.
Compose messages and quick replies
- Recipient field supports searching contacts by name or phone number, with suggestions appearing as you type.
- Contacts with multiple numbers show a labelled number chooser.
- Android favourite contacts appear below the recipient field for quick messaging.
- Add or remove Android favourites using the star controls.
- Includes dated conversation bubbles, quick replies and a bottom message composer.
- Preserves draft text during screen updates and recreation.
- Sends directly when Send is tapped, without the previous confirmation popup.
- Shows SMS part counts and Sent, Sending or Failed status.
Dual-SIM support
- Choose SIM 1, SIM 2 or Android’s default SMS SIM when sending.
- Filter the inbox and conversations by All SIMs, SIM 1, SIM 2 or SIM unknown.
- Opened messages display their receiving or sending SIM.
- Sending-SIM selection is separate from the inbox viewing filter.
- Messages without reliable SIM metadata remain labelled SIM unknown.
OTP notifications
- Recognises OTPs, verification codes, sign-in codes, temporary codes and other supported authentication-code phrases.
- Displays recognised codes prominently with subtle highlighting.
- Distinguishes the latest OTP from earlier active OTP notifications.
- Includes receipt times and a Copy OTP action.
- Provides Mark as read and Delete actions, including compact notification controls.
- Personal messages use a separate notification channel. Promotional and blocked messages remain silent.
Blocking and sender controls
- Block or unblock senders from conversation and message menus.
- Existing and future blocked messages are retained in a separate Blocked messages view.
- Manage blocked senders even when their saved messages have been deleted.
- Set a sender to always move to Promotions.
- Normalised sender identities help apply rules across matching operator prefixes and phone-number formats.
Automatic spending insights
- Detects supported completed debit, purchase and merchant-payment alerts.
- Extracts amounts and merchant names, then assigns spending categories.
- Excludes recognised card repayments, credits, refunds, payment reminders, OTPs and failed, pending or future transactions.
- Recognises ATM withdrawal alerts under Cash.
- Flags uncertain merchant names for review.
- Uses transaction references and amounts to reduce duplicate entries where available.
- Supports correcting merchant names, amounts and categories, or adding missed expenses manually.
- Category rules can apply to a merchant’s previous and future payments.
- Delete unwanted expenses while retaining their original SMS. Monthly and category totals recalculate automatically.
Credit-card organisation
- Groups recognised card messages by issuer and last four digits.
- Separates transactions, statements and dues, payments, refunds and other card messages.
- Displays statement amounts, minimum dues and due dates when stated in the SMS.
- Keeps the original message accessible for checking the extracted information.
Monthly budgets and fingerprint protection
- Tracks spending in Indian rupees using calendar-month totals.
- Supports editable monthly category limits and custom categories.
- Sends budget alerts when included spending reaches or exceeds a limit.
- Provides separate fingerprint-lock switches for Spending and Budgets, both enabled by default.
- Spending protection also covers shop totals, card summaries and expense editing.
- Protected sections lock again when the app leaves the foreground. Turning a lock off requires authentication.
Cleanup and fresh start
- Optional OTP cleanup after 1, 2 or 3 days.
- Optional promotional SMS cleanup after 7 or 30 days.
- Optional all-message cleanup after 7, 30 or 60 days.
- All-message cleanup covers SMS and MMS across folders and both SIMs while preserving recorded expenses and budgets.
- Delete all messages includes a separate option to clear spending history.
- Cleanup is off until configured, and permanent deletion requires confirmation.
Appearance and accessibility
- Five colour schemes: Teal & Navy, Ocean Blue, Amethyst Purple, Rose & Plum, and Amber & Slate.
- Light, dark and system-following appearance options.
- Compact layouts intended for smaller displays, including foldable cover screens.
- Business sender names and bundled or downloaded logos, with initials when a logo is unavailable.
Usage counter and privacy

Usage reporting sends only a random installation ID and app version, at most once daily during foreground use. It does not send SMS, OTPs, contact details, spending records or budgets.

Turning reporting off stops further reports and requests removal of that installation’s counter record. Failed removal requests retry when connectivity is available. Counts represent reporting installations—not verified individual people—and reinstalling can create a new installation.

Messages, contacts and financial records are processed locally. Optional logo downloads share company names and website domains with external services.
