Scalaを始めるにあたって調べたこと
=================================

Scalaをゼロから始めるにあたって調べたことをメモ  
(わからんこと/言葉など)

Scala
------
### なんぞ ###

### 参考 ###

http://twitter.github.io/effectivescala/index-ja.html

skinny
-------

### なんぞ ###
Scalatraをベースに作られたフルスタックWebアプリケーションフレームワーク

#### コンポーネント達 ####

##### Routing & Controller & Validator #####

Scalatraを使用  
Scalatraよりできること多い？

##### O/Rマッパー #####

Skinny ORM  
ScalikeJDBCを使う

###### SkinnyMapper ######

Finder APIs
Querying APIs

##### DBマイグレーション #####

Flyway

##### テンプレートエンジン #####

デフォルトでScalateを提供  

##### メール #####

Skinny Mailer  


### 参考 ###

[skinny-framework.org](http://skinny-framework.org/)



Scalatra
-----------

### なんぞ ###

### 参考 ###

sbt
-------

### なんぞ ###
ビルドツール

### 調べたもの ###

#### クロスビルド ####

以下みたいに%%を使う
```scala

libraryDependencies += "net.databinder" %% "dispatch" % "0.8.0"

```

> To use a library built against multiple versions of Scala, double the first % in an inline dependency to be %%. This tells sbt that it should append the current version of Scala being used to build the library to the dependency’s name. For example:


### 参考 ###
[cross-building] (http://www.scala-sbt.org/release/docs/Cross-Build.html)





## Scalatra
