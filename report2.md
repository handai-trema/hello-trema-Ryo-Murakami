## 課題 (Hello Trema)

HelloTrema が起動したら次のメッセージを表示するようにしてみよう:

```
HelloTrema started.
```

##回答

class HelloTremaの関数startを以下のように変更した．
回答にはself.classを用いた後to_sを用いてString型に変更した．

``` 
def start(_args)
  logger.info "#{self.class.to_s} started."
 end
  ...
```

今回の課題は[信家君のレポート](https://github.com/handai-trema/hello-trema-trema-nobu/blob/master/report_1.md#user-content-%E3%82%AF%E3%83%A9%E3%82%B9%E5%90%8D%E3%82%92%E5%87%BA%E5%8A%9B%E3%81%99%E3%82%8B)を参考にした．
