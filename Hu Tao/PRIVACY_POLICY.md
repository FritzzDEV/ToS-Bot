# Hu Tao Discord Bot — Privacy Policy

**Effective date:** November 24, 2026  
**Last updated:** November 24, 2026

> **NOTE:** Hu Tao is currently getting updated. This bot is an early release and may have bugs and errors.

## 1. Operator and contact

Hu Tao is operated by **Helunemi Studio** (“we,” “us,” or the “operator”). Privacy and data requests can be sent to **helunemi.center@gmail.com**.

This policy covers the Hu Tao bot and its associated Helunemi Game Parlor Discord Activity. It does not replace Discord’s or the Helunemi website’s own privacy terms.

## 2. Information the bot processes

Hu Tao processes only information needed to provide its bot features:

- **Server and message context:** Discord supplies server IDs, channel and message context, member display names, mentions, and other information needed to handle a command, a mention, or a member event. In servers, ordinary chat replies are triggered when a user mentions Hu Tao. Direct messages are handled as chat. Message text is used in memory to create a reply and is not saved by this bot.
- **Server settings:** When the server owner changes reply settings, we store the server ID and the selected event style (tone, length, slang, and cussing preferences) in `hu_tao_data.json` on the machine running the bot.
- **Owner-provided replies and notes:** We store custom event text and knowledge, memory, or skill notes submitted by the server owner. For a URL note, we also store the submitted public HTTPS URL, page title, and up to 4,000 characters of extracted page text. A URL is fetched only when the owner requests it; Hu Tao does not follow redirects or fetch private network addresses. The remote website receives the normal request from the machine running Hu Tao.
- **Moderation-event context:** For a welcome or moderation-event embed, Hu Tao uses the affected member’s display name and avatar, the server name, and—if available—the reason and moderator from the server audit log. It sends the configured embed to the configured greeting channel or the server’s system channel. These event details are not saved in Hu Tao’s settings file.
- **Game Parlor Activity:** When opened, the Activity uses Discord’s SDK to obtain its Activity instance ID and connected participant count. For multiplayer presence and chess, the Activity’s game server temporarily processes the room ID, each connected player’s chosen display name (which can be their linked Helunemi username), socket connection ID, and current chess match and moves. This room data is held in server memory and is removed when the room empties or the server restarts. Solo game progress is kept in the player’s browser while the game is being played.
- **Optional Helunemi account link:** If a player links their Helunemi account, the Activity sends the one-time link code to the Helunemi website API and stores the resulting revocable account-link token in that player’s browser local storage. The Activity uses the token to request the account username, Parlor Coin balance, and storage, and to perform supported account actions such as collecting a daily reward or unlinking. The Helunemi website service processes those account records; this bot policy does not describe the website’s separate data handling, for which the website operator should provide a separate policy. The Activity game-room server does not receive the account-link token.
- **Operational logs:** The bot prints a connection message when it starts. Discord and the computer or hosting provider that runs the bot may maintain their own technical logs under their own policies.

Hu Tao does not ask for Discord passwords or tokens from users, does not sell user data, and does not send chat messages to an AI model or use them to train one.

## 3. Why information is used

Information is used to respond to commands and mentions, apply the server owner’s reply settings, retrieve relevant owner-provided notes, announce member events, show the current Activity room and chess match, connect a player’s Helunemi account when requested, and keep the bot and Activity operating. The bot’s note matching is a local keyword match; it is not an AI training process.

## 4. Where information is stored and who receives it

Saved server settings, custom replies, and notes are kept in `hu_tao_data.json` on the machine running the bot. The bot code does not upload that file to a separate analytics or advertising service. Discord receives messages and embeds that the bot sends, and Discord processes them under Discord’s own policies. Owner-provided notes may appear in a reply to members in the same server when relevant. A requested URL is contacted to retrieve its page, and its server may process the request under its own policies. Activity room state is held temporarily in the Activity server’s memory. If an account is linked, the Activity communicates with the Helunemi website API configured for the app (by default, `https://helunemi.onrender.com`); the website processes its own account data.

Access to the local data file depends on who controls the machine and its backups. The operator should restrict access to that machine and keep the bot token and data file private.

## 5. Retention and deletion

The bot keeps owner-created settings and notes until they are changed or deleted by the operator, or the data file is deleted. The current bot has no automatic expiration for these records. Message text and moderation-event details are not retained by Hu Tao after the event or reply is handled, apart from content the owner intentionally saves as a note or custom reply. Activity room state lasts for the active room and is held in memory; the Activity account-link token stays in browser local storage until unlinked, removed by the user, cleared, or expired under the Helunemi API’s token rules. Helunemi website records are subject to the website’s retention practices.

To request access, correction, or deletion of saved Hu Tao settings or notes, contact **helunemi.center@gmail.com** and identify the server and the relevant item. We will verify the request as reasonably necessary and handle it within the period required by applicable law. Discord messages already sent by the bot remain subject to Discord’s own retention and deletion controls.

If the bot is removed or shut down, the server’s local data file may remain on the operator’s machine until the operator deletes it. Ask the operator to remove that server’s records if desired. A player can unlink the Activity account on that device or clear the browser’s local storage. To request deletion of the linked Helunemi website account data, use the website’s account support or contact the operator.

## 6. Security

The bot uses Discord’s API and its configured local files to provide its features. No internet-connected service can be guaranteed completely secure. The operator should protect the computer hosting Hu Tao, limit access to its files, and keep the bot token confidential. If we become aware of unauthorized access to data handled by Hu Tao, we will take reasonable steps to investigate and provide notices required by law and Discord’s developer rules.

## 7. Children and eligibility

Hu Tao does not knowingly request age or identity documents. Use of Hu Tao is subject to Discord’s minimum-age requirements and applicable local law.

## 8. International processing and third parties

Discord processes Discord account and message information under its own privacy policy. The machine running Hu Tao may be located in a different country from you. The Bot's server runs on Helunemi's Owner Computer.

## 9. Changes

We may update this Privacy Policy when the bot’s features or data handling change. The latest version will be published at the privacy-policy URL supplied for Hu Tao in Discord’s Developer Portal. Material changes should be reflected here before or when the affected feature is introduced.

## 10. Contact

Privacy questions or requests: **Helunemi.center@gmail.com**.

Discord’s own Privacy Policy is available at [discord.com/privacy](https://discord.com/privacy).
