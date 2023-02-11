# Mautic-Text-Local-SMS-Plugin
Developed  this Text Local SMS plugin in Mautic which is alternative to Twilio plugin available in Mautic.This plugin replaces the SMS channel and allows you to send messages through Textlocal Sms api using the Textlocal Sms Web application.
Intended for >= Mautic 4.0

## Installation by console
1. Download the plugin, unzip in your plugins folder
2. Rename the folder to MauticTextlocalBundle
3. Run below commands in terminal step by step :
	a) sudo chmod -R 777 plugins/MauticTextlocalBundle (For giving permission)
	b) sudo php bin/console cache:clear (For clearing cache)
	c) sudo php bin/console mautic:plugins:install (For installing plugin using terminal command)
	d) sudo php bin/console mautic:plugins:reload (For reloading plugin using terminal command)


## Usage
1. Go to your **Plugins** in Mautic UI
2. You should see new Textlocal plugin in the list, click and publish it.
3. This plugin overrides your SMS transport. In your **Configuration > Text message settings** select Textlocal as default transport and enter you texlocal API key.
