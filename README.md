# Siril_script_tom
このスクリプトは https://gitlab.com/free-astro/siril/-/tree/master/scripts?ref_type=heads にて開発されているスクリプトを元にtomが改良を加えたものです。

・OSC_Prepocessing_Make_Master_Flat.ssf
マスターフラットを作る部分だけを抜き出しています

・OSC_Prepocessing_Make_Master_Dark.ssf
マスターダークを作る部分だけを抜き出しています。

・OSC_Preprocessing_MFD_BayerDrizzle.ssf
  1.あらかじめ作成していたマスターフラット、マスターダークを読み込む様に変更
  2.cosmetic correctを削除
  3.sigma clipをMAD clipに変更
  4.stack時に-wfwhmで重みづけ
  5.処理をやり直した際、同じファイル名で上書きされる事を防ぐため、保存時の日付と時間をファイル名に入れている
