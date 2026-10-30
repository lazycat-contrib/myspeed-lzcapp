# MySpeed for LazyCat

- Upstream https://github.com/gnmyt/myspeed, initial version 1.0.9, MIT.
- Package `community.lazycat.app.myspeed`, Linux amd64, minimum LazyCat OS 1.5.0.
- Image `docker.io/germannewsmaker/myspeed:1.0.9` delivered via `docker.1ms.run` with required source/runtime digest matching.
- Single container, native command `bun run server/index.js`, port 5216, data in `/myspeed/data` persisted at `/lzcapp/var/data`.
- No native account system; the app stays behind LazyCat authentication with no public-path exemption. No Docker socket, host directory or preset credentials.
- Speed results reflect the app container's egress, not other devices on the network. First start creates the database automatically.

## Publication

Reusable LazyCat workflow with versioned Release assets. Automatic private and official publishers stay disabled; only the independently verified Release URL/SHA256 is submitted to MiaoMiao community store after full alias/package/source duplicate checks.

No file-chooser interceptor, smoke job or runtime gate. Configuration/workflow checks, mirror verification and LPK SHA256 do not establish device startup, an actual speed test, scheduler execution or history rendering. Those runtime behaviors remain unverified.
