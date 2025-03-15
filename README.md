Always opens the warp menu, even if the chunk is claimed. Discalimer: Any barrel standing on a barrier can be opened, regardless of whether the chunk is claimed or not.

# claims

Future TODO:
- API
  - [ ] Add Cancelable Claim/Unclaim events, currently only "ListenOnly" events are available
- Claims
  - [ ] Add EntityType Command Argument
  - [ ] /chunk list for groups


# API

```groovy
repositories {
  maven("https://repo.kalimero2.com/releases")
}

dependencies {
  implementation("com.kalimero2:claims-api:2.0.0")
}
```


# Integrations
## Squaremap
Fork of https://github.com/jpenilla/squaremap-addons/tree/master/addons/claimchunk
