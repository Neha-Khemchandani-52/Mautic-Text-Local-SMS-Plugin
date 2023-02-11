# Mautic-Text-Local-SMS-Plugin
Developed this Text Local SMS plugin in Mautic which is alternative to Twilio plugin available in Mautic.This plugin replaces the SMS channel and allows you to send messages through Textlocal Sms api using the Textlocal Sms Web application.
Intended for >= Mautic 4.0

## Installation by console
1. Download this folder "MauticTextlocalBundle", unzip in your plugins folder
2. Run below commands in terminal step by step :
    • sudo chmod -R 777 plugins/MauticTextlocalBundle (For giving permission)
    • sudo php bin/console cache:clear (For clearing cache)
    • sudo php bin/console mautic:plugins:install (For installing plugin using terminal command)
    • sudo php bin/console mautic:plugins:reload (For reloading plugin using terminal command)
	
	                                OR
				       
2. You can install it through Mautic Web Interface : 
    • Go to the Configuration -> Plugins Settings, in Mautic web interface.
    • Click on Install/Upgrade Plugins.
    • The plugin should now be available for configuration.

## Usage
1. Go to your **Plugins** in Mautic UI
2. You should see new Textlocal plugin in the list, click and publish it.
3. This plugin overrides your SMS transport. In your **Configuration > Text message settings** select Textlocal as default transport and enter you texlocal API key for using it to send text messages to users.
