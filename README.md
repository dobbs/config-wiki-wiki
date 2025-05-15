# config-wiki-wiki

See [dobbs/droplet-wiki-wiki](https://github.com/dobbs/droplet-wiki-wiki)

To add links to index.html:

    ls *json | perl -lpe 's{^(.*)$}{<p><a href="./$1">$1</a></p>}' >> index.html
