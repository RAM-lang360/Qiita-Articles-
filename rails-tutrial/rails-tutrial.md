# Ruby on Rails チュートリアルで発生するバージョンエラーについての備忘録

「Ruby on Rails チュートリアルプロダクト開発の０→１を学ぼう」の第4章において```'bootstrap-sass'```をgemに追加した時以下のエラーが発生した。

```
```

これは第一章において提示されているrailsのバージョンがbootstrap-sassのサポート外になっているため起きる。
そのため以下のコードを実行してrailsのバージョンをbootstrap-sassに合わせる。
＊「Ruby on Rails チュートリアルプロダクト開発の０→１を学ぼう」ではrailsのバージョンが7系であり、wsl上で動かすとsqlite3関連でエラーが起きるので注意。
```gem```