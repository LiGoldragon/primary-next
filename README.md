# Primary Next

Primary Next begins from the live Primary root through `primary-root`. It does
not copy, publish, or delete legacy logs. `primary-root/flows` is the available
old-log view and remains a writable local symlink; it is not a read-only mount.

The aspect paths are reversible local symlinks:

| Path | Target | Access |
| --- | --- | --- |
| `aspects/field` | `/git/github.com/LiGoldragon/field` | writable local checkout |
| `aspects/psyche` | `/git/github.com/LiGoldragon/psyche` | writable local checkout |
| `aspects/mind` | `/git/github.com/LiGoldragon/mind` | writable local checkout; currently dirty and preserved |
| `primary-root` | `/home/li/primary` | writable local root |

No skills are copied here. The authoritative generated skill trees remain at
Primary and are read through `primary-root`; no readiness claim is made until a
separate environment check verifies their paths and the desired mount policy.
