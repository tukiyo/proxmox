proxmox3.xパッチ
===================

* pvemanagerlib.js.patch
  * proxmox3.1のisoでインストールした時用パッチ

* pvemanagerlib.js.patch.2
  * wheezyにproxmox3.1のパッケージを手動でインストールした時用のパッチ

* pvemanagerlib.js.patch.3
  * proxmox3.2のisoでインストールした時用パッチ

$ sudo patch /usr/share/pve-manager/ext4/pvemanagerlib.js < pvemanagerlib.js.patch
