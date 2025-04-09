# SagerNet Sing-box All Tags

A custom statically-linked build of [SagerNet sing-box](https://github.com/SagerNet/sing-box/) with all tags enabled.

## Compatibility

only `linux/amd64` `linux/arm64` are supported.

## Usage

Download the latest executable and use it!

`linux/amd64`

```sh
cd /var/lib/marznode/ && curl -sSfL https://github.com/joestar9/build-sing-box/releases/latest/download/sing-box-linux-amd64-v3 -o sing-box && chmod +x sing-box
```

`linux/arm64`

```sh
cd /var/lib/marznode/ && curl -sSfL https://github.com/joestar9/build-sing-box/releases/latest/download/sing-box-linux-arm64 -o sing-box && chmod +x sing-box
```

Verify it's working using `./sing-box version` command.
