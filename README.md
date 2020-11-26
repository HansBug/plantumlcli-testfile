# plantumlcli-testfile

Test files for [plantumlcli](https://github.com/HansBug/plantumlcli).

Files in this repository are used for running unittest, and will be automatically downloaded to `demo` path when running travis-ci.


Actually, the most serious problem is that everytime it download plantuml.jar from sourceforge (about 8-10 jobs as the same time), there is a high probability to get 503 error from sourceforge T_T. The way I download them is exactly the same as the way introduced in sourceforge documentation, using 'wget', so I really have no idea about this. If you know how the best or better practise, please inform me in issue or by any other ways. Onegai shimasu ~~
