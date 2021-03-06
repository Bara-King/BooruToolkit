# BooruToolkit
#### local image board library organization framework written in Bash
#### version 2.3

[Forum thread on e926](https://e926.net/forum/show/233498)

## Features
* Download metadata from imageboards like e926 and others using XML APIs
* Tag files using filesystem-level softlinking on Windows, Linux and possibly MacOS
* Tag files using TMSU, a cross-platform utility for file tagging
* Upload local library to your imageboard's favorites
* Download images from specified queries
* Easy-to-understand code and plugin support

## Dependencies
* libxml2-utils (for working with XML APIs)
* curl (for accessing APIs)
* recode (for fixing text encoding in API responses)

## Installation

`$ git clone https://github.com/vladasbarisas/BooruToolkit.git`

`$ bash BooruToolkit/BooruToolkit.sh`

Make sure you leave the main script in its folder.

## Usage

Run the script and follow on-screen instructions.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Added some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

## Known bugs

* Recursive mode is not supported on Windows
* DLU will only work with simple queries (without special characters like `:` `+` etc.)

## License

BooruToolkit (TagOrganizer) is public domain, for more information please consult LICENSE.
