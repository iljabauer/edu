---
date: 2023-01-24T12:45:29-05:00
title: "chainctl policies update"
slug: chainctl_policies_update
url: /chainguard/chainguard-enforce/chainctl-docs/chainctl_policies_update/
draft: false
images: []
type: "article"
toc: true
---
## chainctl policies update

Update the description of a policy.

```
chainctl policies update POLICY_NAME | POLICY_ID --description DESCRIPTION [--output table|json|id] [flags]
```

### Examples

```
  # Update a policy description by name.
  chainctl policy update my-policy --description "A description of my policy."
  
  # Remove a policy description by ID.
  chainctl policy update 617ec5ae5775e22fb52ec2d62398de1e7def7986/e74e9050df769110 --description ""
```

### Options

```
  -d, --description string   New description for this policy.
  -h, --help                 help for update
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

* [chainctl policies](/chainguard/chainguard-enforce/chainctl-docs/chainctl_policies/)	 - Policy related commands for the Chainguard platform.

