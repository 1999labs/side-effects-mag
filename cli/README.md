# side-effects

CLI for the [Side Effects](https://github.com/knownquantity/side-effects) newsletter.

> SFX of an agentic internet.

## Use

```sh
npx side-effects                 # help
npx side-effects subscribe       # subscribe via email
npx side-effects latest          # the 3 most recent issues
npx side-effects read 001        # read an issue in your terminal
npx side-effects api             # show the JSON endpoints
```

Requires Node 18+.

## Subscribing

`subscribe` posts to the Buttondown API if `BUTTONDOWN_API_KEY` is set in the environment of whoever is hosting the publication. End readers do **not** need a key — the command falls back to opening the public subscribe URL.

## License

MIT.
