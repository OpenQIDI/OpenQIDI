# OpenQIDI
Warehouse for Information about QIDI 3D Printers

This site is meant to be a guide for sharing information about QIDI 3D printers.  Currently we are gathering specifications and documentation.

## Contributing

If you would like to contribute to this site, you are welcome to fork the repository and submit a pull request.  

For editing and previewing the result, this repo is set up with a devcontainer configuration.  

## Running locally

This project is built with mkdocs-material and contains a dev container config.

When opening the project in Visual Studio Code, you will be prompted to re-open the project in a dev container.  Once open in a dev container, the command below will open a local webserver that will host a preview of the site that will update in real time as changes are made.  

* `mkdocs serve` - Start the live-reloading docs server.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files. -->
