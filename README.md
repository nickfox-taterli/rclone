我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

[<img src="https://rclone.org/img/logo_on_light__horizontal_color.svg" width="50%" alt="rclone logo">](https://rclone.org/)

[Website](https://rclone.org) |
[Documentation](https://rclone.org/docs/) |
[Download](https://rclone.org/downloads/) | 
[Contributing](CONTRIBUTING.md) |
[Changelog](https://rclone.org/changelog/) |
[Installation](https://rclone.org/install/) |
[Forum](https://forum.rclone.org/)

[![Build Status](https://github.com/rclone/rclone/workflows/build/badge.svg)](https://github.com/rclone/rclone/actions?query=workflow%3Abuild)
[![Go Report Card](https://goreportcard.com/badge/github.com/rclone/rclone)](https://goreportcard.com/report/github.com/rclone/rclone)
[![GoDoc](https://godoc.org/github.com/rclone/rclone?status.svg)](https://godoc.org/github.com/rclone/rclone) 
[![Docker Pulls](https://img.shields.io/docker/pulls/rclone/rclone)](https://hub.docker.com/r/rclone/rclone)

# Rclone

Rclone *("rsync for cloud storage")* is a command line program to sync files and directories to and from different cloud storage providers.

## Storage providers

  * 1Fichier [:page_facing_up:](https://rclone.org/fichier/)
  * Alibaba Cloud (Aliyun) Object Storage System (OSS) [:page_facing_up:](https://rclone.org/s3/#alibaba-oss)
  * Amazon Drive [:page_facing_up:](https://rclone.org/amazonclouddrive/) ([See note](https://rclone.org/amazonclouddrive/#status))
  * Amazon S3 [:page_facing_up:](https://rclone.org/s3/)
  * Backblaze B2 [:page_facing_up:](https://rclone.org/b2/)
  * Box [:page_facing_up:](https://rclone.org/box/)
  * Ceph [:page_facing_up:](https://rclone.org/s3/#ceph)
  * Citrix ShareFile [:page_facing_up:](https://rclone.org/sharefile/)
  * DigitalOcean Spaces [:page_facing_up:](https://rclone.org/s3/#digitalocean-spaces)
  * Dreamhost [:page_facing_up:](https://rclone.org/s3/#dreamhost)
  * Dropbox [:page_facing_up:](https://rclone.org/dropbox/)
  * FTP [:page_facing_up:](https://rclone.org/ftp/)
  * GetSky [:page_facing_up:](https://rclone.org/jottacloud/)
  * Google Cloud Storage [:page_facing_up:](https://rclone.org/googlecloudstorage/)
  * Google Drive [:page_facing_up:](https://rclone.org/drive/)
  * Google Photos [:page_facing_up:](https://rclone.org/googlephotos/)
  * HTTP [:page_facing_up:](https://rclone.org/http/)
  * Hubic [:page_facing_up:](https://rclone.org/hubic/)
  * Jottacloud [:page_facing_up:](https://rclone.org/jottacloud/)
  * IBM COS S3 [:page_facing_up:](https://rclone.org/s3/#ibm-cos-s3)
  * Koofr [:page_facing_up:](https://rclone.org/koofr/)
  * Mail.ru Cloud [:page_facing_up:](https://rclone.org/mailru/)
  * Memset Memstore [:page_facing_up:](https://rclone.org/swift/)
  * Mega [:page_facing_up:](https://rclone.org/mega/)
  * Memory [:page_facing_up:](https://rclone.org/memory/)
  * Microsoft Azure Blob Storage [:page_facing_up:](https://rclone.org/azureblob/)
  * Microsoft OneDrive [:page_facing_up:](https://rclone.org/onedrive/)
  * Minio [:page_facing_up:](https://rclone.org/s3/#minio)
  * Nextcloud [:page_facing_up:](https://rclone.org/webdav/#nextcloud)
  * OVH [:page_facing_up:](https://rclone.org/swift/)
  * OpenDrive [:page_facing_up:](https://rclone.org/opendrive/)
  * OpenStack Swift [:page_facing_up:](https://rclone.org/swift/)
  * Oracle Cloud Storage [:page_facing_up:](https://rclone.org/swift/)
  * ownCloud [:page_facing_up:](https://rclone.org/webdav/#owncloud)
  * pCloud [:page_facing_up:](https://rclone.org/pcloud/)
  * premiumize.me [:page_facing_up:](https://rclone.org/premiumizeme/)
  * put.io [:page_facing_up:](https://rclone.org/putio/)
  * QingStor [:page_facing_up:](https://rclone.org/qingstor/)
  * Rackspace Cloud Files [:page_facing_up:](https://rclone.org/swift/)
  * Scaleway [:page_facing_up:](https://rclone.org/s3/#scaleway)
  * Seafile [:page_facing_up:](https://rclone.org/seafile/)
  * SFTP [:page_facing_up:](https://rclone.org/sftp/)
  * StackPath [:page_facing_up:](https://rclone.org/s3/#stackpath)
  * SugarSync [:page_facing_up:](https://rclone.org/sugarsync/)
  * Tardigrade [:page_facing_up:](https://rclone.org/tardigrade/)
  * Wasabi [:page_facing_up:](https://rclone.org/s3/#wasabi)
  * WebDAV [:page_facing_up:](https://rclone.org/webdav/)
  * Yandex Disk [:page_facing_up:](https://rclone.org/yandex/)
  * The local filesystem [:page_facing_up:](https://rclone.org/local/)
  
Please see [the full list of all storage providers and their features](https://rclone.org/overview/)

## Features

  * MD5/SHA-1 hashes checked at all times for file integrity
  * Timestamps preserved on files
  * Partial syncs supported on a whole file basis
  * [Copy](https://rclone.org/commands/rclone_copy/) mode to just copy new/changed files
  * [Sync](https://rclone.org/commands/rclone_sync/) (one way) mode to make a directory identical
  * [Check](https://rclone.org/commands/rclone_check/) mode to check for file hash equality
  * Can sync to and from network, e.g. two different cloud accounts
  * Optional large file chunking ([Chunker](https://rclone.org/chunker/))
  * Optional encryption ([Crypt](https://rclone.org/crypt/))
  * Optional cache ([Cache](https://rclone.org/cache/))
  * Optional FUSE mount ([rclone mount](https://rclone.org/commands/rclone_mount/))
  * Multi-threaded downloads to local disk
  * Can [serve](https://rclone.org/commands/rclone_serve/) local or remote files over HTTP/WebDav/FTP/SFTP/dlna

## Installation & documentation

Please see the [rclone website](https://rclone.org/) for:

  * [Installation](https://rclone.org/install/)
  * [Documentation & configuration](https://rclone.org/docs/)
  * [Changelog](https://rclone.org/changelog/)
  * [FAQ](https://rclone.org/faq/)
  * [Storage providers](https://rclone.org/overview/)
  * [Forum](https://forum.rclone.org/)
  * ...and more

## Downloads

  * https://rclone.org/downloads/

License
-------

This is free software under the terms of MIT the license (check the
[COPYING file](/COPYING) included in this package).
