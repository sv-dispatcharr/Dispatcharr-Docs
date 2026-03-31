# Plugin Releases

Want to get your plugin added to this list? Check out the [plugin repository](https://github.com/sv-dispatcharr/Plugins/blob/main/CONTRIBUTING.md) to learn how to contribute.
## Available Plugins

| Plugin | Version | Author | License | Description |
|--------|---------|-------|---------|-------------|
| [`API Gateway`](#api-gateway) | `1.5.4` | testuser14 | MIT | Exposes a REST API gateway for third-party integrations and remote management |
| [`Auto Restart`](#auto-restart) | `0.9.1` | testuser6 | MIT | Automatically restarts failed streams and connections with configurable retry logic |
| [`Backup Manager`](#backup-manager) | `3.0.0` | testuser4 | GPL-3.0 | Automated backup and restore of Dispatcharr configuration, channels, and profiles |
| [`Bandwidth Limiter`](#bandwidth-limiter) | `1.4.0` | testuser11 | Apache-2.0 | Limits total bandwidth usage per profile or globally with configurable thresholds and actions |
| [`Channel Logger`](#channel-logger) | `1.0.0` | testuser1 | MIT | Logs channel activity and stream changes to a database for historical analysis |
| [`Channel Sorter`](#channel-sorter) | `0.2.0` | testuser13 | MIT | Automatically sorts and organizes channels by category, name, or custom rules |
| [`Discord Notifier`](#discord-notifier) | `1.0.5` | testuser5 | MIT | Sends Discord webhook notifications for stream events, errors, and status changes |
| [`Dispatcharr Exporter`](#dispatcharr-exporter) | `2.4.1` | sethwv | MIT | Expose Dispatcharr metrics in Prometheus exporter-compatible format for monitoring |
| [`EPG Sync`](#epg-sync) | `2.1.0` | testuser2 | MIT | Synchronizes EPG data from multiple sources and merges guide information |
| [`Grafana Dashboard`](#grafana-dashboard) | `1.1.0` | testuser8 | MIT | Provides pre-built Grafana dashboard JSON and a data-source proxy for visualizing Dispatcharr metrics |
| [`M3U Validator`](#m3u-validator) | `1.2.0` | testuser7 | MIT | Validates M3U playlists and reports broken or duplicate entries with detailed diagnostics |
| [`Profile Scheduler`](#profile-scheduler) | `2.0.1` | testuser10 | MIT | Schedules automatic profile switching based on time-of-day rules and priority configurations |
| [`Stream Health Monitor`](#stream-health-monitor) | `1.3.2` | testuser3 | Apache-2.0 | Monitors stream health metrics and sends alerts on degradation or failures |
| [`Telegram Bot`](#telegram-bot) | `0.5.0` | testuser9 | MIT | Telegram bot interface for controlling Dispatcharr remotely and receiving status updates |
| [`Usage Stats`](#usage-stats) | `4.0.0` | testuser15 | GPL-3.0 | Tracks and displays detailed usage statistics including viewer counts, peak hours, and popular channels |
| [`Webhook Relay`](#webhook-relay) | `1.0.0` | testuser12 | MIT | Generic webhook relay that forwards Dispatcharr events to configurable HTTP endpoints |

---

### [API Gateway](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/api-gateway/README.md)

**Version:** `1.5.4` | **Author:** testuser14 | **Last Updated:** Mar 29 2026, 15:09 UTC

Exposes a REST API gateway for third-party integrations and remote management

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.19.0+

**Downloads:**
 [Latest Release (`1.5.4`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/api-gateway/api-gateway-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/api-gateway)

**Maintainers:** testuser14, testuser2 | **Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/api-gateway) | **Last Change:** [`da6c731`](https://github.com/sv-dispatcharr/Plugins/commit/da6c731667243d6a2ab3a671508416d428366b80)

---

### [Auto Restart](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/auto-restart/README.md)

**Version:** `0.9.1` | **Author:** testuser6 | **Last Updated:** Mar 28 2026, 20:03 UTC

Automatically restarts failed streams and connections with configurable retry logic

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.19.0+

**Downloads:**
 [Latest Release (`0.9.1`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/auto-restart/auto-restart-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/auto-restart)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/auto-restart) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Backup Manager](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/backup-manager/README.md)

**Version:** `3.0.0` | **Author:** testuser4 | **Last Updated:** Mar 28 2026, 20:03 UTC

Automated backup and restore of Dispatcharr configuration, channels, and profiles

**License:** [GPL-3.0](https://spdx.org/licenses/GPL-3.0.html)

**Dispatcharr Compatibility:** v0.16.0+

**Downloads:**
 [Latest Release (`3.0.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/backup-manager/backup-manager-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/backup-manager)

**Maintainers:** testuser4, testuser5 | **Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/backup-manager) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Bandwidth Limiter](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/bandwidth-limiter/README.md)

**Version:** `1.4.0` | **Author:** testuser11 | **Last Updated:** Mar 28 2026, 20:03 UTC

Limits total bandwidth usage per profile or globally with configurable thresholds and actions

**License:** [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)

**Dispatcharr Compatibility:** v0.18.0+

**Downloads:**
 [Latest Release (`1.4.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/bandwidth-limiter/bandwidth-limiter-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/bandwidth-limiter)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/bandwidth-limiter) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Channel Logger](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/channel-logger/README.md)

**Version:** `1.0.0` | **Author:** testuser1 | **Last Updated:** Mar 28 2026, 20:03 UTC

Logs channel activity and stream changes to a database for historical analysis

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.18.0+

**Downloads:**
 [Latest Release (`1.0.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/channel-logger/channel-logger-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/channel-logger)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/channel-logger) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Channel Sorter](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/channel-sorter/README.md)

**Version:** `0.2.0` | **Author:** testuser13 | **Last Updated:** Mar 28 2026, 20:03 UTC

Automatically sorts and organizes channels by category, name, or custom rules

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.16.0+

**Downloads:**
 [Latest Release (`0.2.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/channel-sorter/channel-sorter-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/channel-sorter)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/channel-sorter) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Discord Notifier](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/discord-notifier/README.md)

**Version:** `1.0.5` | **Author:** testuser5 | **Last Updated:** Mar 28 2026, 20:03 UTC

Sends Discord webhook notifications for stream events, errors, and status changes

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.18.0+

**Downloads:**
 [Latest Release (`1.0.5`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/discord-notifier/discord-notifier-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/discord-notifier)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/discord-notifier) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Dispatcharr Exporter](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/dispatcharr-exporter/README.md)

**Version:** `2.4.1` | **Author:** sethwv | **Last Updated:** Mar 26 2026, 18:07 UTC

Expose Dispatcharr metrics in Prometheus exporter-compatible format for monitoring

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.19.0+

**Downloads:**
 [Latest Release (`2.4.1`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/dispatcharr-exporter/dispatcharr-exporter-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/dispatcharr-exporter)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/dispatcharr-exporter) | **Last Change:** [`6746a9a`](https://github.com/sv-dispatcharr/Plugins/commit/6746a9af622de4adf5cfd6b7d959594808ed5482)

---

### [EPG Sync](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/epg-sync/README.md)

**Version:** `2.1.0` | **Author:** testuser2 | **Last Updated:** Mar 28 2026, 20:03 UTC

Synchronizes EPG data from multiple sources and merges guide information

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.17.0+

**Downloads:**
 [Latest Release (`2.1.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/epg-sync/epg-sync-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/epg-sync)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/epg-sync) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Grafana Dashboard](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/grafana-dashboard/README.md)

**Version:** `1.1.0` | **Author:** testuser8 | **Last Updated:** Mar 28 2026, 20:03 UTC

Provides pre-built Grafana dashboard JSON and a data-source proxy for visualizing Dispatcharr metrics

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.19.0+

**Downloads:**
 [Latest Release (`1.1.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/grafana-dashboard/grafana-dashboard-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/grafana-dashboard)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/grafana-dashboard) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [M3U Validator](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/m3u-validator/README.md)

**Version:** `1.2.0` | **Author:** testuser7 | **Last Updated:** Mar 28 2026, 20:03 UTC

Validates M3U playlists and reports broken or duplicate entries with detailed diagnostics

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.17.0+

**Downloads:**
 [Latest Release (`1.2.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/m3u-validator/m3u-validator-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/m3u-validator)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/m3u-validator) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Profile Scheduler](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/profile-scheduler/README.md)

**Version:** `2.0.1` | **Author:** testuser10 | **Last Updated:** Mar 28 2026, 20:03 UTC

Schedules automatic profile switching based on time-of-day rules and priority configurations

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.19.0+

**Downloads:**
 [Latest Release (`2.0.1`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/profile-scheduler/profile-scheduler-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/profile-scheduler)

**Maintainers:** testuser10, testuser3 | **Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/profile-scheduler) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Stream Health Monitor](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/stream-health-monitor/README.md)

**Version:** `1.3.2` | **Author:** testuser3 | **Last Updated:** Mar 28 2026, 20:03 UTC

Monitors stream health metrics and sends alerts on degradation or failures

**License:** [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html)

**Dispatcharr Compatibility:** v0.19.0+

**Downloads:**
 [Latest Release (`1.3.2`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/stream-health-monitor/stream-health-monitor-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/stream-health-monitor)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/stream-health-monitor) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Telegram Bot](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/telegram-bot/README.md)

**Version:** `0.5.0` | **Author:** testuser9 | **Last Updated:** Mar 28 2026, 20:03 UTC

Telegram bot interface for controlling Dispatcharr remotely and receiving status updates

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.18.0+

**Downloads:**
 [Latest Release (`0.5.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/telegram-bot/telegram-bot-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/telegram-bot)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/telegram-bot) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Usage Stats](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/usage-stats/README.md)

**Version:** `4.0.0` | **Author:** testuser15 | **Last Updated:** Mar 28 2026, 20:03 UTC

Tracks and displays detailed usage statistics including viewer counts, peak hours, and popular channels

**License:** [GPL-3.0](https://spdx.org/licenses/GPL-3.0.html)

**Dispatcharr Compatibility:** v0.16.0+

**Downloads:**
 [Latest Release (`4.0.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/usage-stats/usage-stats-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/usage-stats)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/usage-stats) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

### [Webhook Relay](https://github.com/sv-dispatcharr/Plugins/blob/releases/zips/webhook-relay/README.md)

**Version:** `1.0.0` | **Author:** testuser12 | **Last Updated:** Mar 28 2026, 20:03 UTC

Generic webhook relay that forwards Dispatcharr events to configurable HTTP endpoints

**License:** [MIT](https://spdx.org/licenses/MIT.html)

**Dispatcharr Compatibility:** v0.17.0+

**Downloads:**
 [Latest Release (`1.0.0`)](https://github.com/sv-dispatcharr/Plugins/raw/releases/zips/webhook-relay/webhook-relay-latest.zip)
- [All Versions (1 available)](https://github.com/sv-dispatcharr/Plugins/tree/releases/zips/webhook-relay)

**Source:** [Browse](https://github.com/sv-dispatcharr/Plugins/tree/main/plugins/webhook-relay) | **Last Change:** [`0e40625`](https://github.com/sv-dispatcharr/Plugins/commit/0e4062534b268601d7330f0adcd63430a0bb0240)

---

## Using the Manifest

Fetch `manifest.json` to programmatically access plugin metadata and download URLs:

```bash
curl https://raw.githubusercontent.com/sv-dispatcharr/Plugins/releases/manifest.json
```

---

*Last updated: Mar 31 2026, 17:56 UTC*
