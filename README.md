docker-playbook
============================================================

このシナリオはdockerを初期導入するためのシナリオである。


(対応OS)
------------------------------------------------------------

- CentOS 6.x x86_64
- CentOS 7.x x86_64 (CentOS7.1以降)
- RHEL 7.x x86_64 (RHEL7.1以降)
- ubuntu (検討中)

(設定内容)
------------------------------------------------------------
-  dockerパッケージのインストール
-  サービスの自動起動
- 一般ユーザで使用できるように、UNIXソケットではなくTCPソケットでdockerと通信できるように設定を変更
