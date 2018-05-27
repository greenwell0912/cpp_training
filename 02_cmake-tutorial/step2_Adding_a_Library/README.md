# 参考
- [CMake Tutorial A Basic Starting Point (Step2)](https://cmake.org/cmake-tutorial/)
- [CMake Tutorial A Basic Starting Point (Step2) 日本語訳](http://opencv.jp/cmake/cmake_tutorial.html#step-2)

# 注意
`option (USE_MYMATH ...` の後に `configure_file (...` を呼ぶ。順番
を間違えると、cmakedefine が機能しない。
