## 課題

仮想スイッチを停止したら、コントローラで次のメッセージを表示するようにしてみよう:

```
Bye 0xabc
```

##回答

[hello_world.rb](https://github.com/handai-trema/hello-trema-Ryo-Murakami/blob/develop/lib/hello_world.rb)を以下のように変更した．
class HelloTremaの関数switch_disconectedを以下のように変更した．
回答にはto_hexを用いて16進数に変更した．

``` 
 def switch_disconected(datapath_id)
  logger.info "Bye #{datapath_id.to_hex}"
 end
```

今回の課題は[信家君のレポート](https://github.com/handai-trema/hello-trema-trema-nobu/blob/master/report_1.md#user-content-%E3%82%AF%E3%83%A9%E3%82%B9%E5%90%8D%E3%82%92%E5%87%BA%E5%8A%9B%E3%81%99%E3%82%8B)を参考にした．