# Poc to Prod

These scripts will help you to export your POC configuration and import it in your production environment.

## Project Goals

* Export configuration.
* Compare the configuration between servers.
* Import configuration to the production
* Resume the Undone imports.


## Using these scripts
### Export
Export-Config.ps1 -SourceUri 'http://servername:5725' -DestinationUri 'http://servername:5725'

#### Result
    2020-12-02_09-31
        Destination-Policy.xml
        Destination-Schema.xml
        Source-Policy.xml
        Source-Schema.xml
    ---

### Compare


### Import


### Resume



## History

Dec, 2, 2020 : Creation

## Credits

Mathias Dumont (IdSec)

## License

A short snippet describing the license (MIT, Apache, etc.)
