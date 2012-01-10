# Couchrest Model Textmate Bundles

## Instalation

### with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone http://github.com/tinogomes/couchrest_model-tmbundle.git CouchRest\ Model.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

### without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/tinogomes/couchrest_model-tmbundle/tarball/master
    tar zxf tinogomes-couchrest_model-tmbundle-*.tar.gz
    rm tinogomes-couchrest_model-tmbundle-*.tar.gz
    mv tinogomes-couchrest_model-tmbundle-* CouchRest\ Model.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Snippets

### Properties
	pp<tab>    # => property :attribute, type
	ppa<tab>   # => property :attribute, []
	ppb<tab>   # => property :attribute, TrueClass
	ppdt<tab>  # => property :attribute, Datetime
	ppd<tab>   # => property :attribute, Date
	ppd<tab>   # => property :attribute, Decimal
	ppf<tab>   # => property :attribute, Float
	pps<tab>   # => property :attribute, String
	ppt<tab>   # => property :attribute, Time
	times<tab> # => timestamps!

## Author

* [Celestino Gomes (@tinogomes)][tinogomes]

## Note on Patches/Pull Requests

* Fork the project.
* Make your feature addition or bug fix.
* Update README with new Snippets, Commands, etc...
* Commit
* Send me a pull request. Bonus points for topic branches.

## License

[![Creative Commons License][cc-image]][cc]<br/>
This work is licensed under a [Creative Commons Attribution-ShareAlike 3.0 Unported License][cc].

[tinogomes]: http://github.com/tinogomes "Celestino Gomes (@tinogomes)"
[cc]: http://creativecommons.org/licenses/by-sa/3.0/ "Creative Commons License"
[cc-image]: http://i.creativecommons.org/l/by-sa/3.0/80x15.png
