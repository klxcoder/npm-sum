# Commands:

```bash
git clone git@github.com:klxcoder/npm-sum.git
cd npm-sum
echo "//registry.npmjs.org/:_authToken=<your-npm-token>" > .npmrc
bun install
bun run index.ts
bun publish --access public
```