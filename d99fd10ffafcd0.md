---
title: "mariadb ユーザー作成"
emoji: "📝"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: []
published: false


###mariadbでユーザーを作成する
####ユーザーを作成
~~~
-- どこからでも接続できるユーザー
CREATE USER "global_taro"@"%";

-- ロカールからしか接続できないユーザー
CREATE USER "local_taro"@"localhost";

-- 指定IPからしか接続できないユーザー
CREATE USER "local_taro"@"192.168.xxx.xxx";
~~~