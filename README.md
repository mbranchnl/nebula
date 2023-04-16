# Nebula

> Working in progress

This role creates 'dynamic' a [Nebula](https://nebula.defined.net/docs/) mesh VPN network for RedHat-family based VM. This role is currently in Alpha.
So documentation will be added in a later state.

## Todo

- [ ] Logging
- [ ] Logrotation of logging
- [ ] [Unsafe routing](https://nebula.defined.net/docs/guides/unsafe_routes/)

## Additional commands

Show details inside nebula-certificate

```shell
nebula-cert print -json -path ca.crt | jq .details
```
