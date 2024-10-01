# Exercise91: 

## 【目次】

- [Log Analytics Workspace 作成](#log-analytics-workspace-作成)
- [Sentinel 接続](#sentinel-接続)
- [サンプルデータの展開](#サンプルデータの展開)


## Log Analytics Workspace 作成

1. Azure ポータルを開く
1. Log Analytics Workspace を開き、「作成」を選択
    1. 基本

        - リソースグループ: (任意の名前で新規作成)
        - 名前: (任意)
    
    1. 確認と作成

        「作成」を選択


## Sentinel 接続

1. Azure ポータルを開く
1. Sentinel を開き、「作成」を選択
1. 作成済のワークスペースを選択して「追加」


## サンプルデータの展開

1. 作成したSentinelを開く
1. [コンテンツ管理]-[コンテンツ ハブ] を開く
1. `Microsoft Sentinel Training` を選択、「インストール」
1. 「作成」
    1. 基本

        - リソースグループ: 作成したもの
        - ワークスペース： 作成したもの

    1. ワークブック, 分析, プレイブック

        デフォルトまま

    1. 確認と作成

        「作成」を選択

