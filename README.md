## Crowdin AndroidStudio Plugin

The plugin lets you integrate android project with Crowdin. It enables you to upload new source strings to the system instantly as well as download translations from your Crowdin project.

To start using this plugin, create a file with project credentials named **crowdin.properties** in the root directory of the project.
```
project-identifier=your-project-identifier
project-key=your-project-key
```

Plugin will automatically find strings.xml file in the values directory and if renewed it will be uploaded to Crowdin instantly.

To download translations from Crowdin, choose in menu: Tools > Crowdin > Download. Translations will be exported to the Resources folder.


### Change log
**Version 0.5.0**
+ Published pluggin

### Seeking Assistance

Need help working with Crowdin CLI or have any questions? <a href="https://crowdin.com/contacts" target="_blank">Contact Customer Success Service</a>.


### Contributing
1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Added some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

### License and Author

Author: Ihor Popyk (ihor.popyk@crowdin.com)

Copyright: 2017 crowdin.com

This project is licensed under the MIT license, a copy of which can be found in the LICENSE file.