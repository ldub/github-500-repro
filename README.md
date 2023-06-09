There is a bug in Github which casues it to error out with a 500 error if you are signed into github and click on [`tasks.nix`](https://github.com/ldub/github-500-repro/blob/master/tasks.nix) in this repository.

It seems to be related to having more than 64 pairs of braces `{}` in one file, and might be related to a bug in the syntax highlighter. See this gist for a demonstration of the syntax highlighter breaking: https://gist.github.com/ldub/b540678e2501149982b07a5bb28e4167
