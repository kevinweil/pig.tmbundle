To install this bundle, paste the following into the terminal:

    mkdir -p ~/"Library/Application Support/TextMate/Bundles/"
    cd ~/"Library/Application Support/TextMate/Bundles/"
    git clone git://github.com/kevinweil/pig.tmbundle "Pig.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

If you are using Textmate 2:

    mkdir -p ~/"Library/Application Support/Avian/Bundles"
    cd ~/"Library/Application Support/Avian/Bundles"
    if [ -d Pig.tmbundle ]; then rm -rf Pig.tmbundle; fi
    git clone git://github.com/kevinweil/pig.tmbundle "Pig.tmbundle"


Enjoy, and please help me improve it!
Kevin

