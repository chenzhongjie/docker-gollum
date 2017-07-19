# docker-gollum
A docker of gollum that supports Chinese

# start

```shell
docker pull chenzj/gollum
mkdir ~/wikidata
git init ~/wikidata
docker run -d -p 4567:4567 -v ~/wikidata:/root/wikidata --name gollum chenzj/gollum --allow-uploads --mathjax --collapse-tree --h1-title
```
