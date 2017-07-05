# CoreOS #

### 構成内容 ###

* CoreOS

---
### 利用環境 ###

* Gitをインストール
https://git-scm.com/book/ja/v1/使い始める-Gitのインストール
* VirtualBoxをインストール
https://www.virtualbox.org
* Vagrantをインストール
https://www.vagrantup.com

---
### 利用方法について ###

**ファイルを配置する**
```
$ git clone https://github.com/reflet/vagrant-coreos.git .
```

**Vagrant起動**
```
$ vagrant up
```

**SSH接続**
```
$ vagrant ssh
```

---
### 補足情報 （プロビジョニングについて） ###

プロビジョニングの設定にて、初回起動時に下記ツールが自動インストールされます。

* docker-compose

---
