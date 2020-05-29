# neat-neat

This repository is a [Neat](https://github.com/olivr-com/neat) template. Use it to transform your existing repo into a Neat template or to start a new repo.

## Prerequisite

- [Neat](https://github.com/olivr-com/neat)

## Content

- [README.md](README.tpl.md) containing a [usage section](inject/neat-usage.md) with instructions for your users to neat your template (if you already have a README.md in you repo, it will append those instructions)
- [.neat.yml](.neat.tpl.yml) with many options commented out so you can configure your repo without having to go back to the documentation every time

## Template usage

Install [Neat](https://github.com/olivr-com/neat) `npm i -g neat` or you can run it directly through `npx`

### For a new repo

Just add a folder at the end of the command. For example:

```sh
neat neat my-project
```

### For an existing repo

Neat will not overwrite any files in your folder unless you tell it to do so with the `--force` option

In your repo folder, run:

```sh
neat neat
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
