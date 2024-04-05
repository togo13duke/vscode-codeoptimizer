# コード最適化マスター

この拡張機能は、OpenAI社が最近リリースしたGPTs機能と、私が設計した[コード最適化マスターGPT](https://chat.openai.com/g/g-UEZYckKpa-cheng-shi-ma-you-hua-da-shi)とChrome/Edge拡張機能[ChatGPT万能ツールボックス](https://chromewebstore.google.com/detail/fmijcafgekkphdijpclfgnjhchmiokgp?hl=zh-TW)を組み合わせて、コードの品質を様々な面で向上させるお手伝いをします。これには、コード構造、実行効率、セキュリティ、コードスタイル、可読性など、思いもよらない技術的詳細が含まれます。

このパッケージを使用するには、以下の2つの要件があります：

1. 事前にChromeまたはEdgeに[ChatGPT万能ツールボックス](https://chromewebstore.google.com/detail/fmijcafgekkphdijpclfgnjhchmiokgp?hl=zh-TW)拡張機能をインストールしておく必要があります。

2. このパッケージ用に設計された[コード最適化マスターGPT](https://chat.openai.com/g/g-UEZYckKpa-cheng-shi-ma-you-hua-da-shi)を使用するには、有料の[ChatGPT Plus](https://openai.com/blog/chatgpt-plus)サブスクリプションアカウントを持っている必要があります。

使用時には、デフォルトのブラウザウィンドウが自動的に開き、[コード最適化マスターGPT](https://chat.openai.com/g/g-UEZYckKpa-cheng-shi-ma-you-hua-da-shi)が起動し、エディタ内の**選択範囲**または**全文書**をChatGPTに送信して質問します。

提案や議論があれば、[こちら](https://github.com/doggy8088/vscode-codeoptimizer/issues)でコメントをお寄せください。

## 主な特徴

* エディタ内の**全文書**をコード最適化マスターGPTに追加する機能をサポート (`codeoptimizer.add_wholefile`)

* エディタ内の**選択範囲**をコード最適化マスターGPTに追加する機能をサポート (`codeoptimizer.add_selection`)

* 現在のエディタ内のプログラミング言語を自動的に識別します。
