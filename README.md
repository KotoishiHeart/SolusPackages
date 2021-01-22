# Solus向けインストールパッケージ構築用設定ファイル
 
このリポジトリにあるファイルは個人で使用するためのパッケージビルド用のファイルです。
 
ご利用する場合は自己責任にてお願いいたします。
 
## 注意
1. このリポジトリにあるファイルを利用してのビルドにはsolbuildパッケージが必要です

~~~
sudo eopkg install solbuild
~~~

2. 32bit版ビルドは構築されません。また、32bit版ビルドの構築が可能なことを当方では確認しておりません。  

3. パッケージビルド方法

~~~
sudo solbuild build
~~~
