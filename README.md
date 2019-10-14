<b style="color: #1383de">docker</b>&nbsp;+&nbsp;<b style="color: #730c15">travis lint</b>

This docker image is based on the official docker [ruby](https://hub.docker.com/_/ruby) image with added support for Travis CI and YML linting.

## Usage
Example command:

    docker run -v $(pwd)/:/data/ aphex3k/docker-travis-lint .travis.yml
