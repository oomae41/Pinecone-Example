## Pinecone
- https://www.pinecone.io/
- [Authentication](https://docs.pinecone.io/docs/authentication#initialize-your-connection)

## 参考記事
- [ベクトルデータベース Pinecone を試す｜npaka](https://note.com/npaka/n/n37a6543542fa)
- [pipとcondaの使い分け](https://www.python.jp/install/anaconda/pip_and_conda.html)
- [ほしいパッケージがcondaにないときの対処法](https://www.capa.co.jp/archives/41290)
    - pinecone-clientはpipでインストールした
- [各メソッドのdoc](https://docs.pinecone.io/reference/create_index)
- [specはPodSpecで作成するとうまく行く](https://github.com/pinecone-io/pinecone-python-client/blob/main/README.md#create-a-pod-index)
- [queryの使い方](https://docs.pinecone.io/reference/query)
- [Hybrid Search](https://dev.classmethod.jp/articles/dive-deep-into-modern-data-saas-about-pinecone/#toc-3)
    - 今回試した記事
- [Embedding（エンベディング：埋め込み、埋め込み表現）とは？：AI・機械学習の用語辞典 - ＠IT](https://atmarkit.itmedia.co.jp/ait/articles/2401/18/news023.html)
- [ベクトル埋め込みとは何か？| 包括的なベクトル埋め込みガイド | Elastic](https://www.elastic.co/jp/what-is/vector-embedding)
- [TransfoXLは使えなくなった](https://huggingface.co/docs/transformers/model_doc/transfo-xl)
    - 今回は`TRUST_REMOTE_CODE=True python`とすることでpythonコマンド上で使える
- [セマンティック検索](https://www.softbank.jp/biz/solutions/generative-ai/ai-glossary/semantic-search/#:~:text=%E3%82%BB%E3%83%9E%E3%83%B3%E3%83%86%E3%82%A3%E3%83%83%E3%82%AF%E6%A4%9C%E7%B4%A2%E3%81%A8%E3%81%AF,%E3%81%99%E3%82%8B%E3%81%9F%E3%82%81%E3%81%AE%E6%8A%80%E8%A1%93%E3%81%A7%E3%81%99%E3%80%82)
- [Hugging Face Courseで学ぶ自然言語処理とTransformer 【part5】](https://zenn.dev/ttya16/articles/0e3e1bff645f161fb4d7)
- [Transformersの'from_pretrained'の使い方とリスクを考察](https://zenn.dev/yagiyuki/articles/load_pretrained)
- [Huggingface Transformers 入門 (1) - 事始め｜npaka](https://note.com/npaka/n/n5bb043191cc9)
    - `from_pretrained`でHugging face上のモデルを取得