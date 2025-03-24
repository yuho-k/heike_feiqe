# 『平家物語』『天草版平家物語』アライメントデータ

[国立国語研究所編『日本語歴史コーパス』（CHJ）](https://clrd.ninjal.ac.jp/chj/)のデータを用いた、『平家物語』と『天草版平家物語』のアライメントデータです。

詳細は、北﨑勇帆（2024）「単語ベクトルを用いた『天草版平家物語』と原拠本『平家物語』の対応付け」（日本語学会2024年度秋季大会）の予稿（[URL](https://www.jpling.gr.jp/taikai/platform/2024b/2024b_all.pdf#page=81)）を参照してください。

# 仕様と中身

以下のデータが格納されています。
- A列: H_ID…〈高野本〉（CHJ『鎌倉時代編Ⅲ』>『平家物語』）のサンプル ID
- B列: H_start…〈高野本〉の開始位置
- C列: F_ID…〈天草版〉（CHJ『室町時代編Ⅱキリシタン資料』>『天草版平家物語』）のサンプル ID
- D列: F_start…〈天草版〉の開始位置

内容物は以下の通りです。
- heike_feiqe_a.csv: カンマ区切りのCSVデータ（対応箇所がない場合は0埋め）
- heike_feiqe_b.csv: カンマ区切りのCSVデータ（対応箇所がない場合は直前の対応する箇所を入力）
- heike_feiqe.xlsx: 上2ファイルをxslxに結合したもの（サンプル付き）
