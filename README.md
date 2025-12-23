# PeerBanHelper Scoop Bucket

<!-- Uncomment the following line after replacing placeholders -->
[![Tests](https://github.com/WordlessEcho/PeerBanHelper-Scoop/actions/workflows/ci.yml/badge.svg)](https://github.com/WordlessEcho/PeerBanHelper-Scoop/actions/workflows/ci.yml) [![Excavator](https://github.com/WordlessEcho/PeerBanHelper-Scoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/WordlessEcho/PeerBanHelper-Scoop/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for [PeerBanHelper](https://docs.pbh-btn.com/en/).

[ScoopInstaller/Extras/pull/15764](https://github.com/ScoopInstaller/Extras/pull/15764)

## Install

Install JBR 25

[ScoopInstaller/Java/pull/577](https://github.com/ScoopInstaller/Java/pull/577)

```pwsh
scoop install https://github.com/WordlessEcho/scoop-java/raw/refs/heads/add-intellij-jbr25/bucket/intellij-jbr25.json
```

```pwsh
scoop bucket add peerbanhelper https://github.com/WordlessEcho/PeerBanHelper-Scoop
scoop install peerbanhelper/peerbanhelper
```

Open PeerBanHelper (JBR) in start menu.
