# Resource Monitor #

* Authors: Alex Hall, Joseph Lee, beqa gozalishvili, Tuukka Ojala and other
  NVDA contributors
* ダウンロード [安定版][1]

このアドオンはCPU負荷、メモリ使用量などリソースの使用状態を通知します。

# キー操作 #

* NVDA+Shift+E メモリ使用量、平均プロセッサー負荷、バッテリーがある場合はその情報も通知します。
* NVDA+Shift+1 平均CPU負荷、マルチコアの場合は各コアの負荷を通知します。
* NVDA+Shift+2/5 物理メモリと仮想メモリの使用量と合計量を通知します。
* NVDA+Shift+3 コンピューターの内蔵および外付けディスクの使用量と合計量を通知します。
* NVDA+Shift+4 バッテリー残量のパーセント値、充電状態、残り時間(放電中のとき)、バッテリーの低下やバッテリー切れの警告を通知します。
* NVDA+Shift+6 CPUアーキテクチャーの32/64ビット、Windowsのバージョンやサービスパックの情報を通知します。
* NVDA+Shift+7 presents the system's uptime.

NVDA 2013.3 以降の場合はこれらのショートカットキーは変更できます。

## 使用方法 ##

このアドオンはタスクマネージャーやWindowsのシステム情報プログラムの代替ではありません。以下をお読みください：

* CPU負荷は物理コアではなく論理プロセッサーについて示します。これは、CPUの数がCPUコアの数の2倍になるハイパースレッディング対応のCPUで顕著に表れます。
* If there is heavy disk activity such as copying large files, there might
  be delays when obtaining disk usage information.
* Support for Windows XP from this add-on will end on December 31,
  2017. Support for Windows Server 2003 and Windows Vista will end on June
  30, 2018.

## Version 17.09

Important: Version 17.09.x is the last version to support Windows XP.

* Last version to run on Windows XP.
* Windows 10 build 16278 and later is recognized as Version 1709. A minor
  revision for this add-on will be released once Version 1709 stable build
  is released.

## Version 17.07.1

* Reintroduce support for Windows XP (broken since version 17.02).

## Version 17.05

* Announcement of system uptime (time passed since last boot; NVDA+Shift+7).

## Version 17.02

* Updated psutil dependency to 5.0.1.
* When checking disk usage, NVDA will no longer present an error dialog on
  some systems where a removable media is not properly recognized (such as
  when a card isn't inserted into a card reader).)

## Version 16.08

Starting with version 16.08, add-on releases will be shown as
year.month.revision.

* Various revisions of Windows 10 are now properly recognized (such as 1607
  for build 14393).
* Windows 10 build revisions (after installing cumulative updates) are
  properly recognized (such as 14393.51).
* If using Insider Preview builds, this fact is recognized.

## Changes for 4.5 ##

* Add-on repository has moved to GitHub (can be found at
  https://github.com/josephsl/resourcemonitor).
* Windows Server 2016 is properly recognized.

## 4.0の変更点 ##

* psutil を 2.2.1 に更新。
* CPU負荷の情報を得た時の性能が大きく向上しました。
* Windows 10の認識へのサポートを追加しました。
* Windows 10では、Windowsのビルド数も通知されるようになりました。
* アドオンマネジャーを利用してアドオンヘルプをご覧いただけます。

## 3.1の変更点 ##

* Resource MonitorはWindows 8.1を公式にサポートしました。
* 翻訳を更新しました。

## 3.0の変更点 ##

* psutil を 1.2.1 に更新。
* 現在のWindowsのバージョンやCPUアーキテクチャー、サービスパックの通知（NVDA+Shift+6）
* ショートカットキーの入力ジェスチャー変更に対応(NVDA 2013.3以降).
* コマンドを2回続けて押すとそれぞれのリソース情報をコピーする機能を追加。

## 2.4の変更点 ##

* 新しい言語: 中国語 (簡体字)、ウクライナ語。
* 翻訳を更新しました。

## 2.3の変更点 ##

* ブルガリア語の翻訳を追加しました。

## 2.2の変更点 ##

* 以下の言語の翻訳を追加しました:
  アラビア語、Aragonese、クロアチア語、オランダ語、フィンランド語、フランス語、Galician、ハンガリー語、イタリア語、日本語、韓国語、ネパール語、Polish、ポルトガル語
  (ブラジル)、ロシア語、スロヴァキア語、スロベニア語、スペイン語、タミル語、トルコ語。

## 2.1の変更点 ##

* psutil を 0.6.1 に更新。
* ドライバの情報を取得する時の大幅な遅延を修正しました。
* コードを整理しました。

## 2.0の変更点 ##

* 翻訳のサポートと翻訳のコメントを追加しました。

## バージョン1.0 ##

* 最初のバージョン

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=rm
