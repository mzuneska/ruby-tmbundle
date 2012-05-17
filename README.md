Install (Textmate 1.x)
=====================

To install via Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/mzuneska/ruby-tmbundle.git "Ruby.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

You can always manually reload the bundles through textmate if you have problems with the last command above: 
Bundles => Bundle Editor => Reload Bundles
