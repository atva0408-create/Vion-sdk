# ViON - SDK

Part of the ViON video surveillance platform ([vionvision.tech](https://vionvision.tech)).

Based on [camera.ui sdk](https://github.com/cameraui/sdk) by seydx (MIT), used with the author's permission.
npm packages are published under the `@vionvision` scope (`@vionvision/sdk`); Python packages and Go module paths keep their upstream names.
To pull upstream changes: `git remote add upstream https://github.com/cameraui/sdk.git && git fetch upstream && git merge upstream/main`.

[![npm](https://img.shields.io/npm/v/@vionvision/sdk?label=npm&logo=npm)](https://www.npmjs.com/package/@vionvision/sdk)
[![PyPI](https://img.shields.io/pypi/v/camera-ui-sdk?label=pypi&logo=pypi&logoColor=white)](https://pypi.org/project/camera-ui-sdk/)
[![Go](https://img.shields.io/github/v/tag/cameraui/sdk?filter=go/*&label=go&logo=go&logoColor=white)](https://pkg.go.dev/github.com/cameraui/sdk/go)

ViON SDK - A collection of language-specific SDKs for seamless integration with the ViON ecosystem. This monorepo contains SDKs for Node.js, Go, and Python, providing developers with the tools they need to interact with ViON services and build powerful plugins.

Available for three runtimes:

| Runtime | Package                               |
| ------- | ------------------------------------- |
| Node    | `@vionvision/sdk` (`./node`)           |
| Go      | `github.com/cameraui/sdk/go` (`./go`) |
| Python  | `camera-ui-sdk` (`./python`)          |

---

_Part of the ViON ecosystem._
