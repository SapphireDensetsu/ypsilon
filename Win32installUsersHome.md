  * Create directory `C:\Users\<UserName>\Ypsilon`
  * Copy `Ypsilon.exe` from build-win32\Release to `C:\Users\<UserName>\Ypsilon`.
  * Copy `sitelib` and `stdlib` from project root to `C:\Users\<UserName>\Ypsilon`.
  * Start Ypsilon with `--sitelib=.\sitelib` option as follows

```
C:\Users\<UserName>\Ypsilon> Ypsilon --sitelib=.\sitelib
Ypsilon 0.9.5-update2 Copyright (c) 2008 Y.Fujita, LittleWing Company Limited.
>(import (match))
>(match '(1 (2 . 3)) ((a (b . c)) (list c b a)))
(3 2 1)
```