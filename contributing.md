# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test tgenv https://github.com/4ng31/asdf-tgenv.git "tgenv"
```

Tests are automatically run in GitHub Actions on push and PR.
