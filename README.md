# 🔑 PGP/GPG Pubkey 公钥

`MengGuyi (孟古一)`

If you want to make sure that no evildoers eavesdrop on data that you send to me, you can use PGP encryption. You can use my public key to encrypt messages so that only I can decrypt them (even you can't decode them). This page describes how to retrieve and verify my PGP public key.

如果你想确保没有坏人窃听你发送给我的数据，你可以使用 PGP 加密。你可以使用我的公钥来加密消息，以便只有我可以解密它们（甚至你自己都无法解密它们）。本页介绍如何检索和验证我的 PGP 公钥。

[![Keybase](https://img.shields.io/badge/-Keybase-33A0FF?logo=Keybase&labelColor=33A0FF&logoColor=fff)](https://keybase.io/mengguyi)

## 📥 Download

### 🔑 [Download Public Key: Guyi Meng (MengGuyi's main GPG)_0x33333333_public.asc](https://github.com/mengguyi/pubkey/releases/download/2025/Guyi.Meng.MengGuyi.s.main.GPG._0x33333333_public.asc)

🔏 [Download public key signature file: Guyi Meng (MengGuyi's main GPG)_0x33333333_public.asc.sig](https://github.com/mengguyi/pubkey/releases/download/2025/Guyi.Meng.MengGuyi.s.main.GPG._0x33333333_public.asc.sig)

## 📥 下载

### 🔑 [点此下载公钥: Guyi Meng (MengGuyi's main GPG)_0x33333333_public.asc](https://github.com/mengguyi/pubkey/releases/download/2025/Guyi.Meng.MengGuyi.s.main.GPG._0x33333333_public.asc)

🔏 [点此下载公钥签名文件: Guyi Meng (MengGuyi's main GPG)_0x33333333_public.asc.sig](https://github.com/mengguyi/pubkey/releases/download/2025/Guyi.Meng.MengGuyi.s.main.GPG._0x33333333_public.asc.sig)

## ✅ Verify this repository

🌎 Unique publish and update URL: <https://github.com/mengguyi/pubkey>

1. Go to [commits](https://github.com/mengguyi/pubkey/commits/master) :
2. Check whether the latest Commit has the `verified` label.
3. Click the `verified` label and you should be able to see:
     1. Message: `This commit was signed with the committer’s verified signature.`
     2. `GPG key ID` used when `git commit` : `6183333333333333` .

[Learn about vigilant mode](https://docs.github.com/github/authenticating-to-github/displaying-verification-statuses-for-all-of-your-commits)

## ✅ 验证此仓库

🌏 唯一指定发布和更新源: <https://github.com/mengguyi/pubkey>

1. 前往 [commits](https://github.com/mengguyi/pubkey/commits/master) ：
2. 检查最新的 Commit 是否具有 `verified` 标签。
3. 点击 verified 标签，应能够看到：
    1. 提示信息： `This commit was signed with the committer’s verified signature.`
    2. `git commit` 时使用的 `GPG key ID` : `6183333333333333` 。
  
[关于警戒模式](https://docs.github.com/github/authenticating-to-github/displaying-verification-statuses-for-all-of-your-commits)

## 🔐 What is PGP/GPG ?

- [Pretty Good Privacy (PGP)](https://en.wikipedia.org/wiki/Pretty_Good_Privacy) encryption program provides cryptographic privacy and authentication for data communication. PGP is used for signing, encrypting, and decrypting texts, e-mails, files, directories and to increase the security of communications.
- [GNU Privacy Guard (GnuPG or GPG)](https://en.wikipedia.org/wiki/GNU_Privacy_Guard) is a free-software replacement for PGP cryptographic software suite. The software is compliant with RFC 4880, the IETF standards-track specification of OpenPGP.

### ⚙ How does PGP work?

- PGP works based on numerical encryption using public and private keys. For example, when `User A` wants to send an encrypted data to `User B`, the later generates a pair of public and private keys. The private key is kept secret and the public key should be shared with `User A`.
- `User A` encrypts the data using the public key of `User B` and digitally signs the data using the former's private key and sends the data. To decrypt the data, `User B` needs to use the private key associated with the public key used to encrypt the data.

## 🔐 什么是 PGP/GPG ？

- [Pretty Good Privacy (PGP)](https://baike.baidu.com/item/PGP) 加密程序为数据通信提供加密隐私和身份验证。PGP 用于对文本、电子邮件、文件、目录进行签名、加密和解密，并提高通信的安全性。
- [GNU Privacy Guard (GnuPG 或 GPG)](https://baike.baidu.com/item/GnuPG) 是 PGP 加密软件套件的免费软件替代品。该软件符合 OpenPGP 的 IETF 标准 RFC 4880。

### ⚙ 它是如何运作的？

- PGP 基于使用公钥和私钥的数字加密来工作。例如，当 `用户A` 想要向 `用户B` 发送加密数据时，后者生成一对公钥和私钥。私钥保密，公钥应与 `用户A` 共享。
- `用户A` 使用 `用户B` 的公钥对数据进行加密，并使用 `用户B` 的私钥对数据进行数字签名并发送数据。为了解密数据，`用户B` 需要使用与用于加密数据的公钥关联的私钥。

## 🔧 Applications 常用软件

### 💻 Windows / macOS / Linux

If you are not familiar with the commands, you can use the graphical interface software [Kleopatra](https://www.openpgp.org/software/kleopatra/). It is included in:

如果你不熟悉命令，可以使用图形界面软件 [Kleopatra](https://www.openpgp.org/software/kleopatra/) 。它包含在:

- [Gpg4win](https://www.gpg4win.org/) (Windows)
- [GPG Suite](https://gpgtools.org/) (macOS)
- [Kleopatra](https://apps.kde.org/kleopatra/) (Linux KDE)

### 📱 Android / iOS

- [OpenKeychain](https://www.openkeychain.org/) (Android)
- [PGPro](https://pgpro.app/) (iOS)

[More 更多 ...](https://gnupg.org/download/)

## 💻 Common commands 常用命令

These instructions are for `GnuPG (GPG)`, but other `OpenPGP` implementations should work similarly.

这些指令适用于 `GnuPG (GPG)` ，但其他的 `OpenPGP` 实现使用方法应该类似。

### 📁 Key management 密钥管理

- Import the downloaded public key 导入下载的公钥:
  - `gpg --import "Guyi Meng (MengGuyi's main GPG)_0x33333333_public.asc"`
- Generate a new key pair 生成你自己的新的密钥对:
  - `gpg --full-generate-key`