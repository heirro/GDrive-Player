# ⛔️ DEPRECATED
# GDrive Link Download or Streaming Generator

Berfungsi meng-generate files google drive agar bisa dibuat untuk Streaming atau Direct Download tanpa Limit.

## What's

Project ini bisa berjalan pada localhost server atau webhosting server. Berbasis engine PHP.

### API Master
```
GET : https://api.heirro.net/developers/gdrive/get.json
```

### API deployment, result service Endpoint:

Core data:
```
GET : /gdrive/get.json?u={link_gdrive}
```

## Download Link Endpoint

1. Download Link with Google ID (slow respond time):
```
GET : /gdrive/dl/verify.html?gid={google_id}
```
2. Direct Download Link with Encrypt (fast respond time):
```
GET : /gdrive/download/direct.html?to={encryption_code}
```
## Embed Video

1. Embeded with jWplayer (**not recommended**):
```
GET : /gdrive/embed.html?key={keyfiles}
```
2. Embeded with HTML5:
```
GET : /gdrive/video.html?key={keyfiles}
```
## Authors

* **Vava Heirro** - *BackEnd & FrontEnd Developer* - [Heirro](https://github.com/heirro)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## [Demo Project](https://apps.heirro.net/gdrive/) | [Demo Get API](https://api.heirro.net/developers/gdrive/get.json?u=https://drive.google.com/open?id=1Q4zicZoBlI4NwSkyi1HV8ff0ggUHHWpd)
