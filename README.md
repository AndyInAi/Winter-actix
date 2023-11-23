# Winter-actix

```sh
(
    echo '
        [source.crates-io]
        replace-with = "mirror"
        
        [source.mirror]
        registry = "http://mirrors4.tuna.tsinghua.edu.cn/git/crates.io-index.git"
    ' > ~/.cargo/config
)

apt install -y cargo
git clone https://github.com/AndyInAi/Winter-actix.git
cd Winter-actix
cargo build --release

# starting HTTP server at http://<ip>:8080
```
