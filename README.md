> **Languages:** [English](./README.md) · [日本語](./README_ja.md)

# crudian simple todo

This repository is a sample web application by [b4moss/crudian](https://github.com/b4moss/crudian).

`crudian` is a RDB manipulation tools for DDD's repository interface.

This repository aims a real sample of usage for crudian.

The application is designed totaly simple TODO web-app. No auth and users, just simply CRUD tasks, statuses.

You may understand how crudian works with this source codes.

## Setup

### Local

- You need `Bun` runtime

```shell
git clone https://github.com/b4moss/crudian-simple-todo.git todo
cd todo
make install
make run
```

Also you can play at GitHub codespace. Try it.


## Make targets

| Target | Description |
| --- | --- |
| `make install` | `bun install` in `samples/bun/` |
| `make run` | Run `samples/bun/index.ts` |
| `make test` | `bun test` in `samples/bun/` |
| `make ruleset-help` | GitHub ruleset helper help |

## License

[MIT License](./LICENSE)
