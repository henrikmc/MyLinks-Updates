# MyLinks Update Channel

This public repository hosts the update metadata used by the self-distributed Firefox extension **MyLinks**.

Permanent Firefox add-on ID:

```text
mylinks@hmcdata.dk
```

Firefox update manifest:

```text
https://raw.githubusercontent.com/henrikmc/MyLinks-Updates/main/updates.json
```

The main MyLinks source repository is maintained separately. This repository must remain public so Firefox can retrieve the update manifest without authentication.

## Security

Only Mozilla-signed XPI files must ever be advertised by `updates.json`.

Do not commit API tokens, Tailscale authentication keys, database credentials, AMO credentials, bookmark exports, or other private data here.
