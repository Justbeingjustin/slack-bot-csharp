### Table of Contents
**[Generate API Key](#generate-api-key)**<br>
**[Usage](#usage)**<br>
**[Contributing](#contributing)**<br>



## Generate API Key
1. Navigate to https://api.slack.com/
2. Click Start Building.
3. Provide an app name and select the development slack workspace.
4. Click "Create App".
5. Select Bots.
6. Add a bot user, provide a display name and default username.
7. Click save changes.
8. Click the Basic Information tab on the left menu.
9. Click "Install your app to your workspace".
10. Select "Oauth & Permissions" Copy the Bot User Oauth Access Token and paste this in the app.config.


## Usage
Provide the API token in the app.config.
```csharp
<?xml version="1.0" encoding="utf-8"?>
<configuration>
  <appSettings>
    <add key="SlackBotApiToken" value="" />
  </appSettings>
</configuration>
```

## Contributing

Pull requests are welcome. 

For large changes, please open an issue first to discuss what you would like to add.
