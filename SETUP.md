# Connect ContextBolt Bookmarks

This plugin needs an existing ContextBolt Bookmarks Pro account.

1. Connect the bundled MCP server at `https://api.contextbolt.app/mcp`.
2. Complete sign-in on the ContextBolt page. Use your account email and its sign-in code.
3. Read the permissions and choose Allow connection.
4. Return to the assistant and try a starter prompt.

In Claude custom connector settings, leave the advanced OAuth fields unchanged. Do not enable “Use Anthropic’s hosted client metadata”.

Use the email shown under Account in the extension. If it does not receive a code, try the email used for your Pro purchase. You can also sign in again from Account in the extension.

Never paste a connection key, email code, or access token into the conversation. Enter credentials only on the ContextBolt sign-in page.

If the host cannot use OAuth, the existing personal MCP URL remains supported. Follow the [connection guide](https://contextbolt.com/docs/connect-your-agent/).

An expired account still needs its access restored. Signing in does not change billing, credits, or subscriptions. Disconnect through the AI app's connection settings.
