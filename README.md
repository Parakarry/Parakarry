$ git checkout -b alsa-audio <1>
$ edit/compile/test
$ git checkout -- curses/ux_audio_oss.c <2>
$ git add curses/ux_audio_alsa.c <3>
$ edit/compile/test
$ git diff HEAD <4>
$ git commit -a -s <5>
$ edit/compile/test
$ git diff HEAD^ <6>
$ git commit -a --amend <7>
$ git checkout master <8>
$ git merge alsa-audio <9>
$ git log --since='3 days ago' <10>
$ git log v2.43.. curses/ <11>









