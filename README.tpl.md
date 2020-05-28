# {{repo}}

This repository is a [Neat](https://github.com/olivr-com/neat) template. Use it to {{purpose}}.

## Content

<!-- Add here what people get with {{repo}} -->

<!-- neat-usage -->

## Template usage

Install [Neat](https://github.com/olivr-com/neat) `npm i -g neat` or you can run it directly through `npx`

### For a new repo

Just add a folder at the end of the command. For example:

```sh
neat {{repo}} my-project
```

### For an existing repo

Neat will not overwrite any files in your folder unless you tell it to do so with the `--force` option

In your repo folder, run:

```sh
neat {{repo}}
```

### As your new personalized repo template

Fork this template, customize it to your needs.

Then use Neat as described above and use the path to your forked repo instead.

For example, at Olivr, we use a more customized [default repo](https://github.com/olivr-com/oss), and we would run the following for each new project:

```sh
neat olivr-com/oss new-project
```

### Composability

Neat is composable, meaning you can compose a repo from several templates by just running the neat command several times.
Check out [neat repo](https://github.com/olivr-templates/neat-repo) or other [neat templates](https://github.com/olivr-com/neat/blob/master/neat-repos.json).

<!-- neat-usage -->
