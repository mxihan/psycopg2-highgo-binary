# psycopg2-highgo-binary

仿照psycopg2-binary做的适合信创环境下使用的psycopg2包（瀚高数据库安全版）
并没有什么代码，因为只是在装了瀚高数据库的情况下手动打包psycopg2并且修改了_psycopg2_xxx.so的RPATH

其中x86_64的libpq.so.5来自4.5.7-see版本，aarch64的libpq.so.5来自4.5.10-see版本，因为我只有这两个版本。
至于其他python版本，暂时没有精力去适配，所以就先这样了，windows端同理，而且我也没有windows版的hgdb-see安装包
