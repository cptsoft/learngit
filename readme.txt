Git is a distributed version system.
Git is free software.
test abc
Love Git!
-----------------
[root@RustApp rust-1.0.0-x86_64-unknown-linux-gnu]# ./install.sh
install: uninstalling component 'rustc'
install: uninstalling component 'cargo'
install: uninstalling component 'rust-docs'
install: creating uninstall script at /usr/local/lib/rustlib/uninstall.sh
install: installing component 'rustc'
install: installing component 'cargo'
install: installing component 'rust-docs'

    Rust is ready to roll.

[root@RustApp rust-1.0.0-x86_64-unknown-linux-gnu]# cargoc -version
bash: cargoc: command not found
[root@RustApp rust-1.0.0-x86_64-unknown-linux-gnu]# rustc --version
rustc: error while loading shared libraries: librustc_driver-4e7c5e5c.so: cannot open shared object file: No such file or directory
-------------------
