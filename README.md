# Overview

Easily tweet from within Logseq!

![](/screenshots/demo.gif)

# Installation

If you find it in the marketplace, do install it from there for a more seamless experience.

If you can't find the plugin in the marketplace, please [download the latest release here](https://github.com/hkgnp/logseq-tweet-plugin/releases) and manually install the plugin in Logseq.

# Usage

1. Install the plugin as above.
2. Navigate to the plugin settings.
3. Copy and paste the code below and replace the values with your own (from the developer console). Please refer to the instructions in the next section to find out how to get your keys and secrets.

```json
{
  "appKey": "API Key",
  "appSecret": "API Secret",
  "accessToken": "Access Token",
  "accessSecret": "Access Token Secret"
}
```

# How to get your Twitter keys, secrets and tokens

1. [Sign up for a developer account](https://developer.twitter.com/en/docs/developer-portal/overview) and log in.

2. Go to your [developer portal](https://developer.twitter.com/en/portal/dashboard).

3. Create a project.

4. Go to your app settings and ensure that your user authentication settings are set to OAuth 1.0a. It should reflect as below after you're done:
   ![](/screenshots/user-auth-settings.png)

5. Go to your keys and tokens page using the tab below:
   ![](/screenshots/keys-tokens-tab.png)

6. On this page, generate your:

- API Key
- API Secret
- Access Token
- Access Token Secret

7. The information in (6) will need to go in the plugin settings as above.
