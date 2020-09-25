<h3 align="center">
	Live Engage
</h3>
<h4 align="center">
	A chat repo forked from https://github.com/thelounge/thelounge.git
</h4>

### Running from source

The following commands install and run the development version of The Lounge:

```sh
git clone https://github.com/thelounge/thelounge.git
cd thelounge
yarn install
NODE_ENV=production yarn build
yarn start
```

When installed like this, `thelounge` executable is not created. Use `node index <command>` to run commands.

⚠️ While it is the most recent codebase, this is not production-ready! Run at
your own risk. It is also not recommended to run this as root.

## Development setup

Simply follow the instructions to run The Lounge from source above, on your own
fork.

Before submitting any change, make sure to:

- Read the [Contributing instructions](https://github.com/thelounge/thelounge/blob/master/.github/CONTRIBUTING.md#contributing)
- Run `yarn test` to execute linters and test suite
- Run `yarn build` if you change or add anything in `client/js` or `client/views`
- `yarn dev` can be used to start The Lounge with hot module reloading
