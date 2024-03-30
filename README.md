# rust-bare-metal

build command for mac os
"""bash
cargo rustc -- -C link-args="-e __start -static -nostartfiles"
"""