# bagbak

Yet another frida based App decryptor. Requires jailbroken iOS device and [frida.re](https://www.frida.re/)

![demo](images/screenshot.gif)

*The name of this project doesn't have any meaning. I was just listening to that song while typing.*

## Prerequisites

### On device

* [frida.re](https://www.frida.re/docs/ios/)

That's all. No SSH required.

### On desktop

* [node.js](https://nodejs.org/) Latest LTS (Long Term Support)

That's all. Npm can handle all dependencies.

It's known that USB device discovery on Windows is too slow that it always reach the timeout. In theory on Linux it should work. We recommend macOS for your convenience.

## Install

```
npm install -g bagbak
```

## Usage

bagbak [bundle id or name]

```
 Options:
   -l, --list             list apps
   -h, --host <host>      hostname
   -u, --uuid <uuid>      uuid of USB device
   -o, --output <output>  output directory
   -f, --override         override existing
   -h, --help             output usage information
```

Currently it does not copy anything other than decrypted executables. For a full repackable ipa, you need to manually fetch those files via SSH.

## 捐助

如果觉得项目有帮助，可以通过支付宝和其他渠道打赏，金额随意

<img src="images/alipay.jpg" width="160">
<img src="images/wechat.jpg" width="150">
