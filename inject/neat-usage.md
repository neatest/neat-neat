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

### As your new personalized template

Fork this template, customize it to your needs.

Then use Neat as described above and use the path to your forked repo instead.

### Composability

Neat is composable, meaning you can compose a repo from several templates by just running the neat command several times.
Check out [neat repo](https://github.com/olivr-templates/neat-repo) or other [neat templates](https://github.com/search?q=topic%3Aneat-template).
