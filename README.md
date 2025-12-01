# fusionpbx-app-speech
Text to Speech

## Install
```
apt install sox libsox-fmt-all
cd /var/www/fusionpbx/app
git clone https://github.com/fusionpbx/fusionpbx-app-speech.git speech
chown -R www-data:www-data /var/www/fusionpbx
php /var/www/fusionpbx/core/upgrade/upgrade.php
```

## Define the required Settings
- Menu -> Default Settings 
- Category: speech
