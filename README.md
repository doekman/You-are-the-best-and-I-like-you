# tezd
Test repo for renaming.

This repository has been renamed¹
from [tezd](https://github.com/doekman/tezd)
  to [test](https://github.com/doekman/test)²
  to [tesd](https://github.com/doekman/tesd)
  to [You-are-so-lame](https://github.com/doekman/You-are-so-lame)
  to [You-are-the-best-and-I-like-you](https://github.com/doekman/You-are-the-best-and-I-like-you).

Apparently GitHub keeps a list of old repository names, and redirects to the newest one.

So **test** redirects to a newly created repository.

¹) You can [rename GitHub repositories](https://help.github.com/en/articles/renaming-a-repository) via the repo's Settings-tab.

²) However, when you create a repository with an "old" name, that wil override the redirect. You won't get a warning from GitHub about this. When fetching with the old repository URL, you'll get the error: `fatal: refusing to merge unrelated histories`. Fix: `git reset --hard` and `git remote set-url origin new://url.to/repository` (or edit your `.git/config` or even re-clone the repository).
