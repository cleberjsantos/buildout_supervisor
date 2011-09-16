INSTALL
========
$ virtualenv --python=python2.6 --no-site-packages ./penv
$ . ./penv/bin/activate
$ hg clone https://bitbucket.org/cleberjsantos/buildout_supervisor
$ cd buildout_supervisor
$ python2.6 -t 30 -Nvvv
$ ./bin/supervisord
