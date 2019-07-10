## Pick Helpers

![License](https://camo.githubusercontent.com/890acbdcb87868b382af9a4b1fac507b9659d9bf/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)

Cross-platform executables that leverage [pick](https://github.com/calleerlandsson/pick) to do things.

### Installation

Make sure the `pick-helpers` script is executable and in your path. Then put some useful bindings in your shell startup file.

```sh
function _pick__jump() {
  cd "`pick-helpers --function jump $*`"
}

alias jp='_pick__jump'
```

### Functions

- `pick-helpers --function jump`
  - combines [autojump](https://github.com/wting/autojump) with pick (requires autojump)

## Poetry Sync

Run `poetry-sync` from the root of any repo that uses `poetry` to manage deps.
