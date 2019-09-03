# metals-eclipse

Eclipse Scala LSP plugin for Metals (WIP)

# Build

To build:

    $ git clone https://github.com/scalameta/metals-eclipse.git
    $ cd metals-eclipse/parent
    $ mvn clean install

# Use

In you eclipse installation go to install new software and point the repository to:

    metals-eclipse/repository/target/repository

# Import project

* In the menu go to File and then "Import...".
* In the "Import" dialog select General and then "Projects from Folder or Archive", and click "Next >"
* In the "Import Projects from File System or Archive" dialogm click the "Directory..." button, select the folder where your project is located. In particular, the folder where the .bloop files are generated, and then click "Finish".


# Also

You can use metals-eclipse to develop metals-eclipse. Documentation coming soon...
