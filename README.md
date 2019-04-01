# Specification 'Web of Things (WoT) Scripting API'

The main deliverable is the [WoT Scripting API Specification](./index.html). The [index.html](./index.html) file contains the latest Editors Draft. See the rendered version here: [http://w3c.github.io/wot-scripting-api/](http://w3c.github.io/wot-scripting-api/).

Copies of the releases for [published versions](https://www.w3.org/TR/wot-scripting-api/) are found in [releases](./releases/).
The latest published version currently is the [First Public Working Draft](https://www.w3.org/TR/2017/WD-wot-scripting-api-20170914/).

See the [rationale.md](./rationale.md) for explanation on API design choices.

See the [primer.md](./primer/README.md) for explaining and illustrating the usage of the API.

See the [applications/script-manager](./applications/script-manager/README.md) on the design of a Thing for script management.

See the [applications/thing-directory](./applications/thing-directory/README.md) on the design of a Thing directory (reverse proxy) that would cache nearby Things, provide a single point of access and synchronize with the cached Things.

To make contributions, please refer to [https://github.com/w3c/wotwg#contributing](https://github.com/w3c/wotwg#contributing).

## TypeScript Definitions

The specification uses WebIDL definitions. TypeScript definititions are also available (see https://github.com/w3c/wot-scripting-api/blob/master/typescript/index.d.ts).

Due to different implementation progress the definitions might be out of sync. However, there are regular sync points usually based on publication releases.
Note: For future releases we plan to use TypeScript instead of WebIDL in the specification.
