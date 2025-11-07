# Settings & Preferences

Customize your Tama experience and manage server settings.

## User Settings

Use `/settings user` to manage your personal preferences.

![User Settings](./assets/tama_settings_user.png)

### Available User Settings

#### DM Notifications 🔔
Choose whether to receive direct messages from Tama:
- Pet care reminders when your pet needs attention
- Vote reminders when you can vote on top.gg

Toggle this setting on or off based on your preference.

#### Skip Confirmations ⚡
Skip the confirmation dialog when purchasing items from the shop:
- **Enabled**: Buy items instantly without confirmation
- **Disabled**: Show confirmation before each purchase (default)

{% hint style="warning" %}
Enable this only if you're comfortable with instant purchases. It can save time but increases the risk of accidental buys.
{% endhint %}

## Server Settings (Admin Only)

Server administrators can configure Tama for their server using `/settings server`.

![Server Settings](./assets/tama_settings_server.png)

{% hint style="warning" %}
This command requires the "Manage Server" permission!
{% endhint %}

### Activities Channel 📝

Set a channel where Tama will post special activities:
- Pets that have traveled to your server from other servers
- Future activity announcements

**To set up:**
1. Use `/settings server`
2. Select a channel from the dropdown
3. Make sure Tama has permission to send messages in that channel

**To disable:**
Click the "Disable Activities Channel" button to stop receiving activity posts.

## How to Change Settings

### User Settings
1. Use `/settings user`
2. Click the toggle button for the setting you want to change
3. Settings update immediately

### Server Settings
1. Use `/settings server` (requires Manage Server permission)
2. Select a channel from the dropdown or click disable
3. Changes apply to the entire server
