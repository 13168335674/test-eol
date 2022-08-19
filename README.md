# README

## test-eol

这是个从 windows 创建的项目，配置 .gitattributes ，然后通过 git 创建的远程仓库。
index.ts 文件在本地是 crlf 格式的。

## test-eol-2

这是个从 test-eol 远程仓库 拉下来的项目。
index.ts 文件在本地是 lf 格式的。

## Test

1. 修改 test-eol index.ts 文件，提交推送远程。
2. 修改 test-eol-2 index.ts 文件，git pull，解决冲突后推送。 