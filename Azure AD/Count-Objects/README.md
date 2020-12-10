# Count objects in Azure AD

This script estimates the number of objects in Azure Active Directory.

## Project Goals

* Estimate the number of objects.

## Prerequisites

* Module [AzureAD](https://docs.microsoft.com/en-us/powershell/azure/install-az-ps?view=azps-5.2.0)

## Using the script
### With current credential
Count-AzureAD-Objects.ps1 -CurrentCredential

### With another current credential
Count-AzureAD-Objects.ps1

### Result
	| Parameter        | Description |
	|------------------|--------------------------------------|
	| Devices          | 9                        |
	| Groups           | 37  |
	| reportType       | 12 |



Devices                    : 9
Groups                     : 37
Roles                      : 12
DeletedApplications        : 0
Users                      : 20
ServicePrincipals          : 358
ApplicationProxyConnectors : 0
ExtensionProperties        : 15
Contracts                  : 0
Contacts                   : 0
Applications               : 14

Total : 465

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

Mathias Dumont (IdSec)
Pierre (Microsft)

## License

A short snippet describing the license (MIT, Apache, etc.)





# Project Name

Short introduction or overview that explains **what** the project is. This description should match descriptions added for package managers (Gemspec, package.json, etc.)

You can also add some badges/states next to Project Name, e.g,
+ [Travis CI](https://travis-ci.org/)
+ [AppVeyor](http://www.appveyor.com/)
+ [Coveralls](https://coveralls.io/)
+ [Gitter](https://gitter.im/)
+ [Shields.io](http://shields.io/)
+ Others

## Features or Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Requirements

This section is optional if there isn't any special dependencies. Else a bulletlist will suffice, e.g.,
+ [Node.js](https://nodejs.org/)
+ [React](https://facebook.github.io/react/)
+ Others

## Installation or Getting Started

Provide code examples and explanations of how to get the project, e.g.,

	git clone https://github.com/Jasonnor/README.md.git
    cd README.md
    npm install README.md
    npm start

## Usage

Show how to use the project or library.
    
## Reference

+ [jxson](https://gist.github.com/jxson) - [README.md](https://gist.github.com/jxson/1784669)
+ [gistfrojd](https://gist.github.com/gistfrojd) - [README.md](https://gist.github.com/gistfrojd/5fcd3b70949ac6376f66)

Depending on the size of the project, if it is small and simple enough the reference docs can be added to the README. For medium size to larger projects it is important to at least provide a link to where the API reference docs live.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license ([MIT](http://opensource.org/licenses/mit-license.php), [Apache](http://opensource.org/licenses/Apache-2.0), etc.)