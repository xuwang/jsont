A CMD wrapper for [JSON-Template](https://code.google.com/p/json-template/)
========================================================

###Setup
	WORKDIR=$HOME/projects/jsont
	mkdir -p $WORKDIR
	cd $WORKDIR
	sudo easy_install pip		# if pip is missing
	sudo pip install docopt		# if docopt is mission

###Usage
	jsont <template> <json_data>

###Examples
	./test.sh
Note: _test.jsont_ is under _tmpl/_, _data.json_ is under _data/_

###Template Reference
See [template reference](https://code.google.com/p/json-template/wiki/Reference)