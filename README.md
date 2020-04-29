# @sjmeverett/get-package-paths

Gets an array of paths to copy for a given dependency or array of dependencies, already installed in `node_modules`.

## Usage

```ts
import { getPackagePaths } from '@sjmeverett/get-package-paths';

const paths = getPackagePaths(process.cwd(), ['some-sort-of-package']);
```
