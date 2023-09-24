# status.hikalium.dev

This status page covers following services:

- misskey.hikalium.dev

## Updates

### [resolved] Services offline temporarily
timestamp: `2023-09-24T19:45:14+09:00`

Now everything is back to normal.

- Duration of the incident: 90 min
- misskey.hikalium.dev is updated (twice!!)
- Two unplanned incident response excercise completed
  - `rm -rf` on the infra dir
    - TLS cert for misskey is updated for that reason
    - TIL: the core router can hold only 2 ssh pubkeys for a user... (too few...)
  - `No space left on device` error when rebuilding Misskey

![Screenshot 2023-09-24 19 33 15](https://github.com/hikalium/status.hikalium.dev/assets/10512779/f7a59355-42ba-4366-92d9-f09d75cc3ff3)

### Services offline temporarily

timestamp: `2023-09-24T17:50:00+09:00`

The servers are under unscheduled maintainance. All the services may be offline for a while.

Updates will be posted once the service is back stable.

## For hikalium

```
date --iso-8601=seconds
```
