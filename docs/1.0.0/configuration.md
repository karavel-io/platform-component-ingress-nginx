# Configuration

```hcl
component "ingress-nginx" {
  namespace = "ingress-nginx"

  # Params default values

  defaultIngress = true # optional, set to false if you want another ingress as default
}
```
