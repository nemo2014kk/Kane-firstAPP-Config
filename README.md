这是【 KANE face-to-face app】用于拉取 huggingface 服务器地址列表的 json文件，【位于huggingface上的服务器帮你获取微软TTS，我有部署多个服务器，每个服务器的地址列在这里，供APP拉取，APP也开源了，但是暗号是单独分发的。】

用户也可以去huggingface自己部署用于获取微软TTS的服务，而不完全依赖我这三个位于huggingface上的服务器。

这个json还包含一个加密了的Google网盘链接（里面放了新版的APP)，必须在APP内使用“暗号”解密之后才能看到真正的网盘地址。
huggingface 上面我还放了一个备用的json，如果App拉取GH json失败，会自动切换到备用HF json，获取更新信息。
