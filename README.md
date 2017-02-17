# searchy

To Download the whole project, just follow the simple steps:

* Installing repo
 * `mkdir -p ~/bin/repo`
 * `PATH=~/bin:$PATH`
 * `curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo`
 * `chmod a+x ~/bin/repo`

* Now, sync the source:
 * Make a directory where the source will live:
   * `mkdir TextSearchy`
   * `cd TextSearchy`
 * Initialise the repo and sync it.
  * `repo init -u https://github.com/TextSearchy/searchy -b master`
  * `repo sync`
