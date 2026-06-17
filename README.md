# hermes-themes

Custom dashboard themes for [Hermes agent](https://github.com/nousresearch/hermes).

Each `.yaml` file in this repo is a user theme — deploy to `~/.hermes/dashboard-themes/` on any Hermes host and it shows up in the theme picker immediately.

## Themes

| File | Label | Description |
|---|---|---|
| `light.yaml` | Hermes Light | Clean teal-tinted white — light counterpart to the default |
| `daybreak.yaml` | Daybreak | Warm cream + amber, Spectral serif, morning-paper feel |
| `stone.yaml` | Stone | Cool off-white + near-black, Inter, sharp minimal |

## Deploy

```sh
scp *.yaml root@<hermes-host>:/root/.hermes/dashboard-themes/
```

No restart needed — the dashboard picks up new themes on every page load.
