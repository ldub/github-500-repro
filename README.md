There is a bug in Github's nix syntax highlighter which causes it to error out with a 500 error when you click the file `tasks.nix` in this repository.

It seems to be related to having more than 64 pairs of braces `{}` in one file. See this gist for a demonstration of the syntax highlighter breaking: https://gist.github.com/ldub/b540678e2501149982b07a5bb28e4167
