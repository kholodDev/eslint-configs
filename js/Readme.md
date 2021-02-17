## Requirements

`Node.js` version `>= 12.*`

---

## Install

```console
$ npm i -D eslint
```

---

## Errors

**#1**

```console
$ npm run eslint

> project@version eslint /.../project
> eslint src

/.../project/node_modules/eslint/bin/eslint.js:93
        } catch {
                ^

SyntaxError: Unexpected token {
    at createScript (vm.js:80:10)
    at Object.runInThisContext (vm.js:139:10)
    at Module._compile (module.js:617:28)
    at Object.Module._extensions..js (module.js:664:10)
    at Module.load (module.js:566:32)
    at tryModuleLoad (module.js:506:12)
    at Function.Module._load (module.js:498:3)
    at Function.Module.runMain (module.js:694:10)
    at startup (bootstrap_node.js:204:16)
    at bootstrap_node.js:625:3
```

Проверить актуальность версии `Node.js`
