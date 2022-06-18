# Schoolserver electron-updater releases

This is a release-only repo for [electron-updater](https://www.electron.build/auto-update).

> **Note**
> 
> This repo is an attempt to not have to release the source code of SchoolServer

This repo is to solve this problem. Below is a little backdrop:

electron-updater [does not do well with private GitHub repos](https://github.com/iffy/electron-updater-example/issues?q=is%3Aissue+is%3Aopen+private+github). The official [guide for private GitHub repos](https://www.electron.build/auto-update#private-github-update-repo) also does not help in this regard.

However, public GitHub repos does not suffer from the problems highlighted above; but we currently do not want the SchoolServer source code to be simply available publicly.

Therefore, while SchoolServer source code exits in a [private repo](https://github.com/damms005/schoolserver-quasar), we will build and publish its releases to this public repo for [electron-updater](https://www.electron.build/auto-update) to be happy.
