# Such A Bot #

This is a bot that helps sync GitHub Pull Requests to Gerrit. It does
two way syncing - sending GitHub comments to Gerrit and Gerrit Comments
to GitHub. It is built to run on [Wikimedia Tool Labs][1].

## Dependencies ##

This depends on the Redis infrastructure on toollabs - specifically the
[gerrit-to-redis][2] project (which, contrary to its name, also does
github to redis). It is written in python for the most part, and
exact requirements are specified in `requirements.txt` file

## License ##

This project is licensed under the WTFPL.

[1]: http://tools.wmflabs.org
[2]: http://github.com/wikimedia/labs-tools-gerrit-to-redis
