# personal-wiki
A github pages website recording ideas from the experience of Asher Anand.

(No warranty .. do not sue me)

Editing note to self, if running jekyll command that won't work from bash inside
the container, use

 `docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:latest <command>`
 
from inside the docs directory
