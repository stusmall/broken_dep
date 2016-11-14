Today this project will pull the wrong version of openssl.  To see the behavoir run:

rm Cargo.lock; cargo clean; cargo build

Then check your cargo.lock.  When I ran it today I got openssl-sys v0.9.1 instead of the expected
version in the 0.7 range.
