#### 使用 SSH 远程连接到 Github Action 的服务器来生成 OpenRRT 配置文件，也就是根目录下 .config ，需要配合其他仓库使用，我主要解决一个本地配置麻烦的问题，然后不想在其他仓库有多余的操作，直接复制过去就能用了。

理论来讲也是可以直接在终端里完成编译任务的，但是因为这个 github action 有步骤超时问题，会自动关闭 ssh 的连接，所以目前只作为生成配置文件。具体调试的的话我会用到 [Gitpod](https://www.gitpod.io/) 这个网站。

🔛 开启 Github Action ssh 方法是 [Debugging with tmate](https://github.com/marketplace/actions/debugging-with-tmate)

🈲️ 传闻官方没有说 github action ssh 可以用，所以请勿滥用。

😄 玩的开心！！！

