Slack Connector
=================

https://anypoint.mulesoft.com/exchange/org.mule.connectors/mule-slack-connector/


# OAuth Token #

Available at: https://api.slack.com/apps

- Select the app
- OAuth & Permission

## Get the OAuth Access Token ##

## Set Scopes ##

Add `chat.write.bot` scope

## Configure Connector ##

Use a `Chat Post Message` with authentication method `1 Token Connection`

# Autodiscovery #

Setup API Manager to find out AppId

Configure XML Autodiscovery

Configure properties:
- anypoint.platform.client_id=XXXXXXX
- anypoint.platform.client_secret=XXXXXX

