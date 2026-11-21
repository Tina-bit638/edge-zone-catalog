# edge-zone-catalog

OpenClash / Mihomo 独立 YAML 规则集（6 大组合并文件 + 83 个细分服务（`CN` 分组不整组合并，建议配合内置 `GEOIP,CN,DIRECT` 按需使用），支持按大组、细分或自由组合引用）。

## 6 大组合并规则集（一键整组引用，不含 CN）

| 大组 | Provider | 包含服务数 | 去重后规则数 | Raw 调用链接 |
| :--- | :--- | :---: | :---: | :--- |
| `SocialChat` | `socialchat_all` | 21 | 420 | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat.yaml` |
| `BusinessChat` | `businesschat_all` | 4 | 116 | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/BusinessChat.yaml` |
| `Media` | `media_all` | 18 | 1671 | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media.yaml` |
| `UKMedia` | `ukmedia_all` | 5 | 104 | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/UKMedia.yaml` |
| `AUMedia` | `aumedia_all` | 5 | 102 | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AUMedia.yaml` |
| `AI` | `ai_all` | 22 | 1296 | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI.yaml` |

## 全部 83 条细分规则集调用链接

| 分组 | Provider | Raw 调用链接 |
| :--- | :--- | :--- |
| `SocialChat` | `facebook` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/facebook.yaml` |
| `SocialChat` | `twitter` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/twitter.yaml` |
| `SocialChat` | `instagram` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/instagram.yaml` |
| `SocialChat` | `threads` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/threads.yaml` |
| `SocialChat` | `reddit` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/reddit.yaml` |
| `SocialChat` | `discord` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/discord.yaml` |
| `SocialChat` | `kakaotalk` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/kakaotalk.yaml` |
| `SocialChat` | `telegram` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/telegram.yaml` |
| `SocialChat` | `signal` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/signal.yaml` |
| `SocialChat` | `messenger` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/messenger.yaml` |
| `SocialChat` | `snapchat` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/snapchat.yaml` |
| `SocialChat` | `viber` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/viber.yaml` |
| `SocialChat` | `googlechat` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/googlechat.yaml` |
| `SocialChat` | `imessage` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/imessage.yaml` |
| `SocialChat` | `zalo` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/zalo.yaml` |
| `SocialChat` | `threema` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/threema.yaml` |
| `SocialChat` | `wire` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/wire.yaml` |
| `SocialChat` | `element` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/element.yaml` |
| `SocialChat` | `imo` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/imo.yaml` |
| `SocialChat` | `kik` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/kik.yaml` |
| `SocialChat` | `zoom` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat/zoom.yaml` |
| `BusinessChat` | `linkedin` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/BusinessChat/linkedin.yaml` |
| `BusinessChat` | `whatsapp` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/BusinessChat/whatsapp.yaml` |
| `BusinessChat` | `teams` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/BusinessChat/teams.yaml` |
| `BusinessChat` | `line` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/BusinessChat/line.yaml` |
| `Media` | `netflix` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/netflix.yaml` |
| `Media` | `youtube` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/youtube.yaml` |
| `Media` | `tiktok` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/tiktok.yaml` |
| `Media` | `disneyplus` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/disneyplus.yaml` |
| `Media` | `primevideo` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/primevideo.yaml` |
| `Media` | `hulu` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/hulu.yaml` |
| `Media` | `paramountplus` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/paramountplus.yaml` |
| `Media` | `crunchyroll` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/crunchyroll.yaml` |
| `Media` | `hbo` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/hbo.yaml` |
| `Media` | `appletv` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/appletv.yaml` |
| `Media` | `twitch` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/twitch.yaml` |
| `Media` | `pornhub` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/pornhub.yaml` |
| `Media` | `emby` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/emby.yaml` |
| `Media` | `spotify` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/spotify.yaml` |
| `Media` | `applemusic` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/applemusic.yaml` |
| `Media` | `soundcloud` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/soundcloud.yaml` |
| `Media` | `deezer` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/deezer.yaml` |
| `Media` | `tidal` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/tidal.yaml` |
| `UKMedia` | `channel4` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/UKMedia/Channel4.yaml` |
| `UKMedia` | `bbciplayer` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/UKMedia/BBCiPlayer.yaml` |
| `UKMedia` | `itvx` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/UKMedia/ITVX.yaml` |
| `UKMedia` | `my5` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/UKMedia/My5.yaml` |
| `UKMedia` | `skygo` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/UKMedia/SkyGo.yaml` |
| `AUMedia` | `sevenplus` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AUMedia/SevenPlus.yaml` |
| `AUMedia` | `abciview` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AUMedia/ABCiView.yaml` |
| `AUMedia` | `sbsondemand` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AUMedia/SBSOnDemand.yaml` |
| `AUMedia` | `10play` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AUMedia/10Play.yaml` |
| `AUMedia` | `9now` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AUMedia/9Now.yaml` |
| `AI` | `claude` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/claude.yaml` |
| `AI` | `copilot` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/copilot.yaml` |
| `AI` | `gemini` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/gemini.yaml` |
| `AI` | `google` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/google.yaml` |
| `AI` | `openai` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/openai.yaml` |
| `AI` | `grok` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/grok.yaml` |
| `AI` | `perplexity` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/perplexity.yaml` |
| `AI` | `mistral` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/mistral.yaml` |
| `AI` | `metaai` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/metaai.yaml` |
| `AI` | `poe` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/poe.yaml` |
| `AI` | `characterai` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/characterai.yaml` |
| `AI` | `cursor` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/cursor.yaml` |
| `AI` | `windsurf` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/windsurf.yaml` |
| `AI` | `huggingface` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/huggingface.yaml` |
| `AI` | `openrouter` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/openrouter.yaml` |
| `AI` | `groq` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/groq.yaml` |
| `AI` | `manus` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/manus.yaml` |
| `AI` | `midjourney` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/midjourney.yaml` |
| `AI` | `suno` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/suno.yaml` |
| `AI` | `elevenlabs` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/elevenlabs.yaml` |
| `AI` | `runway` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/runway.yaml` |
| `AI` | `otherai` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/otherai.yaml` |
| `CN` | `apple` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/apple.yaml` |
| `CN` | `chinacompanyip` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/chinacompanyip.yaml` |
| `CN` | `googlecn` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/googlecn.yaml` |
| `CN` | `cnmedia` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/cnmedia.yaml` |
| `CN` | `microsoftcn` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/microsoftcn.yaml` |
| `CN` | `steamcn` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/steamcn.yaml` |
| `CN` | `lan` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/lan.yaml` |
| `CN` | `chinadirect` | `https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/chinadirect.yaml` |

## OpenClash `rule-providers` 完整配置

可直接复制 [rule-providers.yaml](https://www.google.com/search?q=https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/rule-providers.yaml) 中的内容粘贴到 OpenClash 主配置的 `rule-providers:` 下。

## 使用说明（OpenClash / Mihomo）

使用时记住一条原则：**`rules:` 从上往下依次匹配，越靠前优先级越高**。
- 需要单独走指定节点的**细分服务**，写在对应**大组**前面。
- 局域网 `lan` 放最前面（建议加 `no-resolve`），中国大陆直连用 `chinadirect` 配合内置 `GEOIP,CN,DIRECT` 放末尾，最后用 `MATCH` 兜底。
- 只需要从 [rule-providers.yaml](https://www.google.com/search?q=https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/rule-providers.yaml) 中复制你实际用到的条目即可，不必全部粘贴。

### 配置示例（大组 + 细分混搭 + 地区 IP 中国直连）

```yaml
rule-providers:
  # 1. 大组合并规则（按需复制）
  ai_all: { type: http, behavior: classical, format: yaml, url: 'https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI.yaml', path: ./rule_provider/AI.yaml, interval: 86400 }
  media_all: { type: http, behavior: classical, format: yaml, url: 'https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media.yaml', path: ./rule_provider/Media.yaml, interval: 86400 }
  socialchat_all: { type: http, behavior: classical, format: yaml, url: 'https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/SocialChat.yaml', path: ./rule_provider/SocialChat.yaml, interval: 86400 }

  # 2. 需要单独分流的细分服务（按需复制）
  claude: { type: http, behavior: classical, format: yaml, url: 'https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/AI/claude.yaml', path: ./rule_provider/AI/claude.yaml, interval: 86400 }
  netflix: { type: http, behavior: classical, format: yaml, url: 'https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/Media/netflix.yaml', path: ./rule_provider/Media/netflix.yaml, interval: 86400 }

  # 3. 局域网与国内常用域名直连（按需复制）
  lan: { type: http, behavior: classical, format: yaml, url: 'https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/lan.yaml', path: ./rule_provider/CN/lan.yaml, interval: 86400 }
  chinadirect: { type: http, behavior: classical, format: yaml, url: 'https://raw.githubusercontent.com/Tina-bit638/edge-zone-catalog/main/ruleset/CN/chinadirect.yaml', path: ./rule_provider/CN/chinadirect.yaml, interval: 86400 }

rules:
  # 局域网优先直连
  - RULE-SET,lan,DIRECT,no-resolve

  # 细分规则放在对应大组前面（优先匹配）
  - RULE-SET,claude,美国节点
  - RULE-SET,netflix,新加坡节点

  # 大组统一分流
  - RULE-SET,ai_all,日本节点
  - RULE-SET,media_all,流媒体节点
  - RULE-SET,socialchat_all,代理节点

  # 国内域名 + 内置地区 IP 直连 + 最终兜底
  - RULE-SET,chinadirect,DIRECT
  - GEOIP,CN,DIRECT
  - MATCH,代理节点
```

### 注意事项

- **策略组名称需匹配**：将示例中的 `美国节点`、`日本节点`、`流媒体节点`、`代理节点` 等替换为你的 OpenClash 配置 `proxy-groups:` 中实际存在的分组名称。
- **自动同步更新**：`interval: 86400` 表示每 24 小时自动从本仓库拉取一次最新规则；在 OpenClash 的 **配置文件管理 → 配置编辑**（或规则覆写设置）中保存并应用即可生效。
