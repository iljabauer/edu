---
date: 2023-01-24T12:45:29-05:00
title: "chainctl version"
slug: chainctl_version
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_version/
draft: false
images: []
type: "article"
toc: true
---
## chainctl version

Prints the version

```
chainctl version [flags]
```

### Options

```
  -h, --help   help for version
      --json   print JSON instead of text
```

### Options inherited from parent commands

```
      --api string                   The url of the Chainguard platform API. (default "http://api.api-system.svc")
      --audience string              The Chainguard token audience to request. (default "http://api.api-system.svc")
      --config string                A specific chainctl config file.
      --console string               The url of the Chainguard platform Console. (default "http://console-ui.api-system.svc")
      --issuer string                The url of the Chainguard STS endpoint. (default "http://issuer.oidc-system.svc")
  -o, --output string                Output format. One of: ["", "table", "tree", "json", "id", "wide"]
      --timestamp-authority string   The url of the Chainguard Timestamp Authority endpoint. (default "http://tsa.timestamp-authority.svc")
```

### SEE ALSO

* [chainctl](/chainguard/chainguard-enforce/chainctl-docs/chainctl/)	 - Chainguard Control

