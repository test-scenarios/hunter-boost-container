# beast-softphone-problem

## Intention

To recreate the problem reported here:

https://github.com/cpp-pm/issues

## Required toolchain

Any toolchain will work with this project, or none.

Some very good toolchains files available here:

https://github.com/ruslo/polly

in which case you can invoke cmake with:

`cmake -DCMAKE_TOOLCHAIN_FILE=<POLLY_DIR>/cxx17.cmake -H<SRC_DIR> -B<BUILD_DIR>`

Where:

* `POLLY_DIR` is the cloned polly repo
* `SRC_DIR` is the directory containing this file
* `BUILD_DIR` is the intended build directory (in-source builds are evil)


# Reference:

https://dl.bintray.com/boostorg/release/1.72.0/source/boost_1_72_0.tar.gz

