# Gatsby + Netlify + Netlify CMSで構築するブログ
Gatsbyスターターブログを改造
https://www.gatsbyjs.org/starters/gatsbyjs/gatsby-starter-blog/

改造箇所

- Netlify CMSで画像をアップロードして、マークダウンに挿入した場合に画像が404となってしまう現象を改善

注意点

- Windows環境だと`gatsby-remark-vscode`プラグインがエラーとなってインストールできない状態に陥る場合がある。そのときはエラーにどうすれば良いかヒントが記載されているので、ググること。
- Netlify CMSでの日本語入力は不安定なため使い難さがある。キャレットの位置などが微妙。