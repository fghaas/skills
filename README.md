# Cleura Skills

A reusable set of skill definitions for use in your repository, reflecting reasonable (though opinionated) guidelines for agentic coding assistants.

These skills are regularly tested against [Cleura AI](https://ai.cleura.cloud) and [OpenCode](https://opencode.ai).

## How to include

To use these skills in your repository, include them as a Git submodule:

```shell
git submodule add https://github.com/cleura/skills .agents/skills
```

If you want to add skills selectively, you can use symlinks instead.
For example:

```shell
git submodule add https://github.com/cleura/skills cleura-skills
mkdir -p .agents/skills
cd .agents/skills
ln -s ../../cleura-skills/<skill-name> .
```

Once you have added the submodule to your repository, be sure to clone with `--recurse-submodules`.
You can also globally enable submodule recursion in your Git configuration:

```bash
git config --global submodule.recurse true
```

## License

This project is licensed under the GNU GPLv3, see [`LICENSE.md`](LICENSE.md) for details.
