# OS X Dictionaries [![GAnalytics, DONT REMOVE](https://ga-beacon.appspot.com/UA-6208376-3/osx-dictionaries/)](https://github.com/igrigorik/ga-beacon)

Various dictionaries compatible with the Dictionary.app in Mac OS X, found on various websites, using the wayback machine, and crying.

## Organization
Each dictionary is organized based on its "base language" - the language it is meant to be read in. Thus, a full Chinese dictionary will be in the Chinese folder, along with Chinese-English, Chinese-Spanish, and Chinese-French dictionaries. 

Dictionaries should be labeled using the ISO standard. Most should be labeled using their respective [`ISO 639-1`](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) two-character codes where possible. If the language does does not have an `639-1` code, use its [`ISO 639-2`](http://en.wikipedia.org/wiki/List_of_ISO_639-2_codes) code instead.

Please [report](#reporting-errors-and-broken-dictionaries) any dictionaries breaking the standards.

## Installation
Installing dictionaries is relatively painless.

#### < 10.8.1 Install
*Note: I do not recommend this installation method. Consider using the pre-10.8.0 method below instead.*


Open Dictionary.app. Click `File`, then `Open Dictionaries Folder`. Simply drag-'n-drop your `xxx.dictionary` file into the folder, restart Dictionary.app, activate the dictionary in Dictionary's Preferences, and you should be good to go.

![Open Dicts](http://i.imgur.com/AGjisDj.png)

*Note that this will* ***only install the dictionary for the current user.*** *If you wish to install for all users, follow the pre-10.8.0 instructions below.*


#### < 10.8.0 / Full System / Problem Install
Open a Finder window. Navigate to `/Library/Dictionaries/` (if your Library folder is hidden, simply press `⌘⇧G` on your keyboard, and navigate using the Go-To window. Then put your `xxx.dictionary` file inside, restart the Dictionary.app, and  activate the dictionary in Dictionary's Preferences. The file should then show up in the tab bar.

![More Dictionaries!](http://i.imgur.com/FLCYZ8T.png)


#### Editing Labels
You can edit labels by simply right-clicking on the tab, and clicking "Edit Label".

![Edit Label](http://i.imgur.com/AGUS405.png)

## Reporting Errors and Broken Dictionaries
Please use [GitHub Issues](https://github.com/afischer15/osx-dictionaries/issues) to report any problems. Give descriptive labels, and be nice!


## Contributing Dictionaries
There are two ways to contribute. Just got one dictionary to add? [Email it to me.](mailto:afischer15@mac.com) 

Otherwise:

1.  Fork this repo 
2.  Add any dictionaries, keeping to the organizational conventions
3.  Commit your changes. `git commit -am 'Added some feature'`
4.  Push to the branch `git push origin my-new-feature`
5.  Create a new Pull Request (you should be prompted to do so.)


## Creating Dictionaries
Apple has a nice outline of [how to create dictionaries](https://developer.apple.com/library/mac/documentation/UserExperience/Conceptual/DictionaryServicesProgGuide/Introduction/Introduction.html) on their website. 

## License & Notes
All dictionaries in this repo are under the [Apache Licence, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html). 

Big Thanks to [calasqm](http://mysite.mweb.co.za/residents/clasqm/mac-os-x-dictionaries/) for listing many of the dictionaries, and The Internet Archive's [wayback machine](http://archive.org/web/) for allowing me to access many files that had disappeared from the web.
