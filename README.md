yahoomessages-grab
==================

Seesaw script for archiveteam Yahoo! Messages grabbing.
You'll find this project on the Archive Team Warrior (http://tracker.archiveteam.org/yahoo-messages/).


Running without a warrior
-------------------------
To run this outside the warrior, clone this repository and run:

    pip install seesaw
    ./get-wget-lua.sh

If 'get-wget-lua.sh' fails with an error about liblua, you need liblua-dev.  Under debian/ubuntu/mint, try:

    apt-get install liblua5.1-dev

then start downloading with:

    run-pipeline pipeline.py YOURNICKNAME

For more options, run:

    run-pipeline --help

