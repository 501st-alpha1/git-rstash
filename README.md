# git-rstash
Transfer your Git stashes to and from remotes with ease!

## Usage

Place or link `git-rstash` somewhere on your `PATH`, then:

```
usage: git rstash push <stash> [<remote>]'
   or: git rstash fetch [<remote>]'
   or: git rstash drop <stash> [<remote>]'
   or: git rstash import <SHA>'
   or: git rstash push-all [<remote>]'
   or: git rstash drop-all [<remote>]'
   or: git rstash import-all'
```

where `<stash>` is a stash number, `<SHA>` is a (short or long) SHA commit hash, and `[<remote>]` is an (optional) remote to operate on.

By default, `git-rstash` uses `origin` as the remote.  Stashes are saved both remotely and locally to `refs/stashes/<SHA>`.

See [my Stack Overflow answer](https://stackoverflow.com/a/61356308/2747593) for more details.
