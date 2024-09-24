# quickstart

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.1.29. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.

# set registry

On Windows, use PowerShell to input `$HOME`. In the output directory, create a new `.bunfig.toml` file and write the following content to set the Taobao mirror.

```toml
[install]
registry = "https://registry.npmmirror.com"
```
