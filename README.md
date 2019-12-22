# Add File Types to New... in Windows 10

1. Open Registry Editor (regedit) to HKEY_CLASSES_ROOT

![Image of Registry Editor](https://tr2.cbsistatic.com/hub/i/r/2018/04/09/272e54ed-80f0-4b6e-97fb-42d84488edb9/resize/770x/bb8f6c9dbf0f21a3c1f00616b02d708c/baddnewmenuitem.png)

2. Scroll down the long list until you see your extension. In this example, .dotx is used.

![Image of Registry Editor for .dox](https://tr1.cbsistatic.com/hub/i/r/2018/04/09/7ff69b0b-698f-4e36-8e90-6f2b525d9817/resize/770x/2db1b4b178c16f0710bf389c8d7e00e9/caddnewmenuitem.png)

3. Right-click on the .dotx entry and then select the `New | Key` item. Give the newly created key the name `ShellNew`.

4. Right-click on the `ShellNew` entry and then select the `New | String Value` item. Give the newly created string the name `NullFile`.

![Image of Registry Editor for NullFile](https://tr2.cbsistatic.com/hub/i/r/2018/04/09/48e217a3-c5c4-4bad-bd16-aa97d9aa0faf/resize/770x/2e5f93ae93bdcf26bc2bcd216d7fd4b2/daddnewmenuitem.png)

5. That should be it!
