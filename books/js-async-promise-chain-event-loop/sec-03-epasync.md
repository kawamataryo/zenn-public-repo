---
date: 2022-06-16
title: "第３章 - async 関数と await 式の挙動"
alieases: [EPAsync 第３章]
---

# この章について

第３章ではいよいよ async/await へと突入します。Promise チェーンとイベントループの知識を使って async/await を理解します。第３章は Promise の知識が必須なのでなるべく第２章を終えてから読むようにしてください。

こちらの章は今後、ジェネレーターや型注釈などのチャプターを追加する可能性があることに注意してください。

# チャプター

- [Promise チェーンから async 関数へ](14-epasync-chain-to-async-await)
- [V8 エンジンによる async/await の内部変換](15-epasync-v8-converting)
- [Top-level await](16-epasync-top-level-async)
- [Promise の静的メソッドと並列化](17-epasync-static-method)
- [await 式の配置による制御](18-epasync-await-position)
- [反復処理の制御](19-epasync-async-loop)
