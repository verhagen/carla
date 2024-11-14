# 


----
$ bundle exec jekyll serve --livereload
----


----
rm -rf _site/
bundle exec jekyll build --config _config.yaml,_config.en.yaml
bundle exec jekyll build --config _config.yaml,_config.nl.yaml
----
