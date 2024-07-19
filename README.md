# GS1前期制作 「Super Bomberman」制作チーム
## 概要
チームメンバー：中山誠士郎,髙木愁,原口藍斗

制作物：SNES「Super Bomberman」

# 制作方針
## 目標
Battele Mode/Battle Stage 01: Normal Zone でのPlayer対戦のクローンを最終完成目標とする。

可能な限りBattle Modeのすべての動作を実装すること。

対戦人数は最大人数である4人までの実装を目指すこととする。

バッファを持たせるために、CPUの実装は初期構想では含まない。タスクに余剰時間が生まれた場合のみ実装を考慮する。

## 参考サイト
[Super Bomberman Resourses](https://www.spriters-resource.com/snes/sbomber/)

[Emulator](https://www.retrogames.cz/play_1037-SNES.php)

# リポジトリ管理

原則としてGitへのプッシュはProjectファイル(Unity_GS1_TeamSBM/Assets/GS1_TeamSBM)の内容物のみとする。

ダウンロードしたAssetsはGit上にプッシュせず、URLを共有するかUnityPackageで共有すること。

## Projectフォルダ

編集したプロジェクトは、**Unity_GS1_TeamSBM/Assets/GS1_TeamSBM**内のツリーに分別して格納すること。

ScenesはAssets直下のScenesではなく、**Projectフォルダ内の"Scenes"** に格納すること。

随時必要であればProjectフォルダ内に個別フォルダを作って作業する。その際はコミット時に必ず**作成理由、内容物についてのコメントを添付**すること。

## ソース

プロジェクトは原則**ローカルブランチ**上で編集すること。

シーンを編集するときは元のシーンを複製し、複製したシーンを用いて作業すること。

コミット・フェッチ・プルはこまめに行ってください。

コミットする場合は必ず規則にのっとって**コメントを添付**すること。

ローカルリポジトリにマージする際コンフリクト(競合)が起こった際は、必ず全員に確認を取った上でどちらの変更を使って解決するか決めること。

プルの際にリソースの内容で重複が起きた場合は、確認を取りどちらかに統一すること。

(SourceTreeの使い方について分からなければ、遠慮なく中山に聞いてください。解決できる範囲で対応します。)

※Sourcetreeの使用方法についての参考文献
(https://yttm-work.jp/git/git_index.html)

## git規則

コミットメッセージは以下の無いようにのっとって書くこと。

記述例「プレイヤーがジャンプできるようにした場合」→Update:プレイヤーのジャンプ機能を追加

![2024-07-18_155024](https://github.com/user-attachments/assets/bb17101d-eed6-4aa6-9668-6d2b7f11da3f)

