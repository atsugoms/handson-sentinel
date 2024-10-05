# Exercise01: Microsoft Sentinel 利用環境の準備

#### ⏳ 推定時間: 20分

#### 💡 学習概要

後続のすべてのモジュールで使用される Microsoft Sentinel トレーニング ラボ ソリューションのデプロイについて説明します。

#### 🗒️ 目次

- [Log Analytics Workspace 作成](#log-analytics-workspace-作成)
- [Microsoft Sentinel ワークスペース 作成](#microsoft-sentinel-ワークスペース-作成)
- [Sentinel Training ラボ のデプロイ](#sentinel-training-ラボ-のデプロイ)
- [Microsoft Sentinel プレイブックの構成](#microsoft-sentinel-プレイブックの構成)

## Log Analytics Workspace 作成

1. Azure ポータルを開く
1. Log Analytics Workspace を開き、「作成」を選択
    1. 基本

        - リソースグループ: (任意の名前で新規作成)
        - 名前: (任意)
    
    1. 確認と作成

        「作成」を選択


## Microsoft Sentinel ワークスペース 作成

1. Azure ポータルを開く
1. Sentinel を開き、「作成」を選択
1. 作成済のワークスペースを選択して「追加」


## Sentinel Training ラボ のデプロイ

1. 作成したSentinelを開く
1. [コンテンツ管理]-[コンテンツ ハブ] を開く
1. `Microsoft Sentinel Training` を選択、「インストール」
1. `Microsoft Sentinel Training Lab Solution` の作成画面で「作成」を選択
1. `Microsoft Sentinel Training Lab Solution` の作成
    1. 基本

        - リソースグループ: 作成したもの
        - ワークスペース： 作成したもの

    1. ワークブック, 分析, プレイブック

        デフォルトまま

    1. 確認と作成

        「作成」を選択


## Microsoft Sentinel プレイブックの構成

1. ラボがデプロイされたリソースグループへ移動

1. リソース グループにある `azuresentinel-Get-GeoFromIpAndTagIncident` という API 接続リソースを選択

1. [全般]-[API接続の編集] を開く

1. 「承認する」を選択

1. ログイン画面が表示されるので、作業用のご自身のアカウントでログイン

1. 元の「API接続の編集」画面へ戻って、「保存」を選択



