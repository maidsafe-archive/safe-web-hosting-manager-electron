# safe-web-hosting-manager-electron
This example tutorial app show cases how to create and manage web services for Public ID on SAFE Network. Demonstrates the usage of MutableData API, NFS API, Authentication APIs.


## Install

* **Note: requires a node version ^8.0.0 and an npm version ^5.0.0**

First, clone the repo via git:

```bash
$ git clone https://github.com/maidsafe/safe_examples && cd safe_examples/web_hosting_manager
```

And then install Node.js dependencies.

```bash
$ yarn
```
Set `NODE_ENV=dev` to use Mock Vault. By deafult it uses Actual Network Or set `NODE_ENV=prod` to use Actual Network.

## Run

```bash
$ yarn start
```

To open application on development environment run `yarn dev`

### Authorising against Mock

To simplify the auth process, as web-hosting can't received a response when running in dev mode.

Run the app, and in the main menu, select `Simulate Mock Response`, and you're good to go.

## Packaging

To package apps for the local platform:

```bash
$ yarn package
```

## Test

```bash
yarn test
```

Run `yarn rebuild-test` if there is Node Module Mismatch Error while running test, this will build the native modules for Nodejs. To build it back to Electron run `yarn rebuild`, now you can start the application.


## License

This SAFE Network application is dual-licensed under the Modified BSD ([LICENSE-BSD](LICENSE-BSD) https://opensource.org/licenses/BSD-3-Clause) or the MIT license ([LICENSE-MIT](LICENSE-MIT) https://opensource.org/licenses/MIT) at your option.

## Contribution

Copyrights in the SAFE Network are retained by their contributors. No copyright assignment is required to contribute to this project.
