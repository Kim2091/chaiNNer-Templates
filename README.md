# chaiNNer-Templates
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J3BCC3L)

These are my pre-made chains/templates for chaiNNer: https://github.com/chaiNNer-org/chaiNNer

You'll likely notice that there are 3 folders: NCNN, ONNX, and Pytorch. These all have different use-cases:
- Pytorch - Best option for Nvidia GPUs, but can also work on CPUs. If you're on Linux and configured ROCM, this can be used for AMD as well
- NCNN - Best option for AMD and Intel GPUs, but also supports Nvidia
- ONNX - Works on Nvidia and CPU. This is usually slower, but is the only option for certain models

Each type of chain is in each folder. They're all identical but with each processing type replaced. Here's an example:

![image](https://github.com/Kim2091/chaiNNer-Templates/assets/62084776/68e5abf3-7da5-49a5-9b51-fa90db7f59c9)
