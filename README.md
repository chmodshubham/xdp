# xdp

```bash
sudo apt update
sudo apt install clang llvm gcc libbpfcc-dev libelf-dev linux-headers-$(uname -r)
```

```
git clone --recurse-submodules https://github.com/xdp-project/xdp-tutorial
git submodule add https://github.com/xdp-project/xdp-tools/ xdp-tools
git submodule add https://github.com/libbpf/libbpf/ libbpf

sudo apt install clang llvm libelf-dev libpcap-dev gcc-multilib build-essential
sudo apt install linux-tools-$(uname -r)
sudo apt install linux-headers-$(uname -r)
sSudo apt install linux-tools-common linux-tools-generic
```
