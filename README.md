# Polygon PMTiles Generator

GeoJSONファイルからPMTilesを生成するためのGitHubワークフロー

## 使い方

1. `data/source/` ディレクトリにGeoJSONファイルを配置
2. 必要に応じて `config/` 内の設定ファイルを編集
3. 変更をコミットしてプッシュ
4. GitHub Actionsで自動的にPMTilesが生成されます

## 設定ファイル

- `config/default.yaml`: 基本設定
- `config/layers/*.yaml`: レイヤー固有の設定

...
