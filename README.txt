【開発環境サンプル】

■proj_c

--------------------------------------------------------------------------------
▼内容

・プロジェクトC開発用リポジトリ。

--------------------------------------------------------------------------------
▼ブランチ

・本流のみ
※必要に応じてパッチ版や海外版などのブランチを作成。

--------------------------------------------------------------------------------
▼依存リポジトリ

・common_lib_individual_for_studio_x ... 共通ライブラリの動作設定（ヘッダーファイル）：ブランチ=proj_c。
・common_lib                         ... 共通ライブラリ（ヘッダーファイル）：ブランチ=proj_c。
・proj_a_lib                         ... プロジェクトA開発用ライブラリ（ヘッダー＆ソースファイル）：ブランチ=master。

--------------------------------------------------------------------------------
▼サブモジュール適用フォルダ

・/lib/individual/ ← common_lib_individual_for_studio_x
・/lib/common/     ← common_lib
・/lib/proj/       ← proj_a_lib

--------------------------------------------------------------------------------
以上
