# サンプルの構成

```bash
$ meson setup src build
```

# サンプルのビルド

```bash
$ cd build
$ meson compile
```

# サンプルの実行

```bash
$ ./hello
Hello World!
```

# テストの構成

```bash
$ meson setup test build_test
```

# テストのビルド

```bash
$ cd build_test
$ meson compile
```

# テストの実行

```bash
$ ./test_hello
[==========] Running 1 test from 1 test suite.
[----------] Global test environment set-up.
[----------] 1 test from HelloTest
[ RUN      ] HelloTest.BasicAssertions
[       OK ] HelloTest.BasicAssertions (0 ms)
[----------] 1 test from HelloTest (0 ms total)

[----------] Global test environment tear-down
[==========] 1 test from 1 test suite ran. (0 ms total)
[  PASSED  ] 1 test.
```
