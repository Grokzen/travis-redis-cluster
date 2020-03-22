Repo archived
=============

This repo is archived and no longer in use or up-to-date. Please see https://github.com/Grokzen/docker-redis-cluster for a updated and more modern version of what this repo used to implement.


travis-redis-cluster
====================

Example repo for how to get redis-cluster working inside CI tests on a service like TravisCI, but it should be possible to use it on any CI service/server that supports building redis from source.

This repo do not currently handle installing build dependencies but TravisCI have them installed when the run starts.

Travis CI build status: [![Build Status](https://travis-ci.org/Grokzen/travis-redis-cluster.svg?branch=master)](https://travis-ci.org/Grokzen/travis-redis-cluster)

Replace the following block your testcode commands in Makefile

```python
#########
# Run your tests/code here
# For example: py.test
#########
```


LICENSE
=======

MIT see LICENSE file
