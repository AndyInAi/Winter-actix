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

export DEBIAN_FRONTEND=noninteractive
apt install -y cargo
git clone https://github.com/AndyInAi/Winter-actix.git
cd Winter-actix
cargo build --release

./target/release/Winter-actix

# starting HTTP server at http://localhost:8080
```
