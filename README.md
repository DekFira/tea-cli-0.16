# tea-cli-0.16
$ tea +rust-lang.org

tea: installing rust-lang.org and 13 other packages into a temporary sandbox
when done type: exit

tea $ cat <<EOF >hello.rs
fn main() {
  println!("Hello World!");
}
EOF
$ rustc hello.rs -o hello
$ ./hello
Hello World!

tea $ exit

$ rustc
command not found: rustc
