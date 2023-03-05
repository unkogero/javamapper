# javamapper

# パフォーマンス
https://www.baeldung.com/java-performance-mapping-frameworks（https://github.com/eugenp/tutorials/tree/master/performance-tests/src/main/java/com/baeldung/performancetests）
https://github.com/arey/java-object-mapper-benchmark
https://github.com/jirkapinkas/java-mapping-frameworks
https://github.com/arey/java-object-mapper-benchmark


# トレンド
https://trends.google.co.jp/trends/explore?date=today%205-y&q=MapStruct,ModelMapper,orica,dozer,JMapper
https://trends.google.co.jp/trends/explore?date=today%205-y&q=MapStruct,ModelMapper,orica,beanutils
https://trends.google.co.jp/trends/explore?date=today%205-y&q=MapStruct,ModelMapper,orica,beanutils,jmapper
https://uga-box.hatenablog.com/entry/2021/08/12/000000


dozer
https://mvnrepository.com/artifact/com.github.dozermapper/dozer-core
6.5.2
2021/4/7
Apache 2.0

　Deep Copy
　カスタムコンバータ
 　更新頻度はひくそう

Orika
https://mvnrepository.com/artifact/ma.glasnost.orika/orika-core
1.5.4
2019/2/20
Apache 2.0

 上記バージョンでは、JDK16以上で警告あり


MapStruct
https://mvnrepository.com/artifact/org.mapstruct/mapstruct
1.5.3.Final
2022/10/7

　コード生成
　コンパイル時にエラー見れる
　https://www.baeldung.com/mapstruct
　Springサポート
　Lombokサポート
　マッピング定義をインターフェースに書く。変換（ソースとデスティネーション）ごとに必要
　https://github.com/mapstruct/mapstruct-examples
　複数インスタンスからのコピーをインターフェースにかける
　https://qiita.com/hushukang/items/a51ff044a51b3ef50862
　作成済みのBeanを更新できる

ModelMapper
https://mvnrepository.com/artifact/org.modelmapper/modelmapper
2022/12/8

　遅い以外はよさそう
　大量処理やマイクロサービス化で頻繁に実行されるかどうか

JMapper
https://mvnrepository.com/artifact/com.googlecode.jmapper-framework/jmapper-core
1.6.1.CR2
2016/12/14
(*)fork
https://mvnrepository.com/artifact/com.windpanda.jmapper-framework/jmapper-core
1.6.3
2022/5/27

https://www.baeldung.com/jmapper
@JMap

本家が更新されていない
アノテーションなどが面倒そう？
あまり使われていない？

BeanUtils
 copyproperties
   フィールド名が固定ならこれでも

　ソースとターゲットの型の違いによりコピー対象がある
　https://spring.pleiades.io/spring-framework/docs/current/javadoc-api/org/springframework/beans/BeanUtils.html#copyProperties(java.lang.Object,java.lang.Object)

　Apache側はSahrowコピー明記
　https://commons.apache.org/proper/commons-beanutils/apidocs/org/apache/commons/beanutils/PropertyUtilsBean.html




