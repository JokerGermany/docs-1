# Authentication
0. Open a private chat with the bridge bot. Usually `@gmessagesbot:your.server`
   * If the bot doesn't accept the invite, see the [troubleshooting page](../../general/troubleshooting.md)
1. Send `login` to start the login.
2. Log in by scanning the QR code. If the code expires before you scan it, the
   bridge will send an error to notify you.
   1. On your phone, open <img src="./messages.svg" class="gm-icon" alt="" />
      Messages by Google.
   2. Tap Menu <img src="./menu.svg" class="gm-icon" alt="" />
      from your conversation list and select **Device pairing**.
   3. Tap **QR code scanner** and point your phone at the image sent by the bot.
3. Finally, the bot should inform you of a successful login.
   * The bridge will create portal rooms for recent chats. The number is
     configurable and defaults to 25 chats with 50 messages backfilled in each
     chat.

As all messages are proxied through the app, your phone must be connected to
the internet for the bridge to work.

If you use Google Fi, note that the bridge does not support logging in with a
Google account, so you must choose to use the normal QR login mode (option 1 in
<https://support.google.com/fi/answer/6188337>).

## Logging out
Simply run the `logout` management command.

<style>
img.gm-icon {
  height: 24px;
  vertical-align: middle;
}
</style>
