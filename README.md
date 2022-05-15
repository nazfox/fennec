# fennec

モジュラー型音声信号処理ライブラリ

**作り始めたばかりなので実態はまだ無い**

## 特徴

- プラグインを動的に追加可能
- プラグインは複数のモジュールを持つことができる
- モジュールを動的に繋ぎ変えたり、  
  モジュールのパラメータを動的に変えることができる
- 入出力はファイルまたはデバイスを選択可能
- Cで書かれたライブラリ
- クロスプラットフォーム(Linux, Windows, OS X)

## API

草案

```
fennec_init()
fennec_start()
fennec_add_plugin()
fennec_update_module_chain()
fennec_update_module_parameters()
```

## TODO

- [ ] APIを決める
- [ ] テストを作る
- [ ] 実装かなぁ

