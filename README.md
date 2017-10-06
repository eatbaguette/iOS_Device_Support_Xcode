# 概要
xcodeのバージョンによって、実機にインストールできるOSのバージョンが限られる。
このディレクトリにあるファイルをコピペすることで、どのxcodeのバージョンでも、このディレクトリにあるファイルのバージョンのOSが使えるようになる

# 使い方
参考URL: https://qiita.com/keroppi0_0/items/e18498956ef29d610a2d
参考URL: http://kan-kikuchi.hatenablog.com/entry/Could_not_locate_device_support_files

# 不具合
本来のxcodeが想定していないバージョンのOSだとビルドエラーになることがある。
Clean -> Build や 再起動を繰り返すとうまくいくことが多い。
