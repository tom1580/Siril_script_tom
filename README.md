# Siril_script_tom
このスクリプトは https://gitlab.com/free-astro/siril/-/tree/master/scripts?ref_type=heads にて開発されているスクリプトを元にtomが改良を加えたものです。</br>
著作権は元スクリプト作者である Cyril Richard氏に帰属します。


・OSC_Prepocessing_Make_Master_Flat.ssf</br>
&emsp;マスターフラットを作る部分だけを抜き出しています</br>
</br>

・OSC_Prepocessing_Make_Master_Dark.ssf</br>
&emsp;マスターダークを作る部分だけを抜き出しています。</br>
</br>

・OSC_Preprocessing_MFD_BayerDrizzle.ssf</br>
&emsp;1.あらかじめ作成していたマスターフラット、マスターダークを読み込む様に変更</br>
&emsp;2.cosmetic correctを削除</br>
&emsp;3.sigma clipをMAD clipに変更</br>
&emsp;4.stack時に-wfwhmで重みづけ</br>
&emsp;5.処理をやり直した際、同じファイル名で上書きされる事を防ぐため、保存時の日付と時間をファイル名に入れている</br>
