# 仕様

下記のlsコマンドを作成する。

- オプション無し
- `-a`
- `-r`
- `-l`
- `-al`
- `-alr`
- `-ar` `-al` `-lr` でも順番に関係なく実行できる
- `-alr` `-lra` `-ral` でも順番に関係なく実行できる

```
% ruby ls-command.rb -alr
total 56
-rw-r--r--    1 katodaiki  staff   2648  2 13  2022 README.md
drwxr-xr-x    3 katodaiki  staff     96  2 13  2022 09.wc_object
drwxr-xr-x    3 katodaiki  staff     96  9 22 11:27 08.ls_object
drwxr-xr-x    3 katodaiki  staff     96  7 10 19:28 07.bowling_object
drwxr-xr-x    3 katodaiki  staff     96  4 21  2022 06.wc
drwxr-xr-x    6 katodaiki  staff    192  9 22 11:39 05.ls
drwxr-xr-x    5 katodaiki  staff    160  9 22 11:39 04.bowling
drwxr-xr-x    3 katodaiki  staff     96  3 26  2022 03.rake
drwxr-xr-x    5 katodaiki  staff    160  9 22 11:39 02.calendar
drwxr-xr-x    5 katodaiki  staff    160  9 22 11:39 01.fizzbuzz
-rw-r--r--    1 katodaiki  staff      6  9 22 11:39 .ruby-version
-rw-r--r--    1 katodaiki  staff     57  2 13  2022 .rubocop.yml
-rw-r--r--    1 katodaiki  staff   2090  2 13  2022 .gitignore
drwxr-xr-x   16 katodaiki  staff    512  1  4 12:39 .git
-rw-r--r--@   1 katodaiki  staff  10244  4  8  2022 .DS_Store
drwxr-x---+ 123 katodaiki  staff   3936  1  4 12:39 ..
drwxr-xr-x   17 katodaiki  staff    544  9 22 11:39 .
```
