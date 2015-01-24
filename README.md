# Easy Reveal.js

These scripts enables you to:
* quickly edit presentations powered by [Reveal.js](http://lab.hakim.se/reveal-js/#/) using markdown;
* painlessly run them on your host leveraging the [docker-reveal.js](https://registry.hub.docker.com/u/danidemi/docker-reveal.js/) Docker image.

## Use

- Clone this repository in a new folder

<code>
$ git clone https://github.com/danidemi/easy-reveal.js.git &lt;my-slideshow-folder>
$ cd &lt;my-slideshow-folder>
</code>

- Start the docker container

<code>
$ ./run-container
</code>

- Create and edit a markdown file following the explanations presented in the [pandoc manual](http://johnmacfarlane.net/pandoc/demo/example9/producing-slide-shows-with-pandoc.html).

<code>
$ touch index.md #then edit it...
</code>

- Convert the markdown file in a reveal.js presentation.

<code>
$ ./build-slideshow
</code>

- Browse to <http:127.0.0.1>

## References

The Docker image used by these scripts is available at: <https://registry.hub.docker.com/u/danidemi/docker-reveal.js/>
