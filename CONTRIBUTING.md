# Contributing to Pebrel Community / 社区贡献指南

Share themes in `themes`, plugins in `plugins`, and application bug reports in
[Kuddev/pebrel](https://github.com/Kuddev/pebrel/issues).

## Share a work

1. Publish your work in a source repository with an explicit license.
2. Identify the author and the original source of adapted material. List media
   licenses separately when they differ from the code or theme license.
3. Use a versioned release for downloadable artifacts. Include actual byte size
   and SHA-256; mutable `latest` links cannot identify an installed version.
4. Fork the appropriate directory repository and submit a pull request using
   its documented entry format. Organization membership is not required.
5. Explain the tested Pebrel version and platforms. Mark untested capabilities
   explicitly; a directory entry does not establish runtime compatibility.

The initial repositories contain empty catalogs. Example snippets explain the
format and are not published works. Large assets belong in author releases,
not in the community repository's Git history.

## Review

Review attribution, source, licensing, compatibility claims, download identity,
and repository-specific size limits. Checks validate directory metadata; the
application must also validate the actual downloaded package before installation.

For PRs, Issues, and comments, the main project's
[commercial promotion policy](https://github.com/Kuddev/pebrel/blob/main/CONTRIBUTING.md#commercial-promotion-policy)
is the authoritative rule. Necessary source attribution is welcome; unauthorized
advertising and referral promotion are not community submissions.

This repository does not configure server-side branch protection merely by
adding a workflow or a review checklist.

## 中文

主题提交到 `themes`，插件提交到 `plugins`，主程序问题提交到 Pebrel 主仓库。

先发布有明确许可的作品，再提交目录登记 PR。作品需注明作者、原作来源、
版本、下载地址、实际字节数和 SHA-256；改编素材须保留署名及许可。
说明实际测试过的 Pebrel 版本和平台，未测试的能力明确标注。
用户无需加入组织即可贡献。

大图片、动图、视频和插件发布文件放在作者的 Release，社区 Git 仓库只维护
目录及规范。目录检查不代替应用下载后的实际校验，也不代表运行兼容性已通过。

商业推广边界以主项目贡献指南中的政策为准。
