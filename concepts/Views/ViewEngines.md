# ビューエンジン

Sailsのデフォルトのビューエンジンは[EJS](https://github.com/visionmedia/ejs)です。

##### ビューエンジンを取り替える

別のビューエンジン使うにはnpmを使ってインストールし、`sails.config.views.engine`([`config/views.js`](http://sailsjs.org/documentation/anatomy/myApp/config/views.js.html)にあります。)を設定する必要があります。

例えばjadeに切り替えるには`npm install jade --save-dev`を実行し、[`config/views.js`](http://sailsjs.org/documentation/anatomy/myApp/config/views.js.html)に`engine: 'jade'`を設定します。



##### サポートしているビューエンジン

  - [atpl](https://github.com/soywiz/atpl.js)
  - [dust](https://github.com/akdubya/dustjs) [(website)](http://akdubya.github.com/dustjs/) (.dust)
  - [eco](https://github.com/sstephenson/eco)
  - [ect](https://github.com/baryshev/ect) [(website)](http://ectjs.com/)
  - [ejs](https://github.com/visionmedia/ejs) (.ejs)
  - [haml](https://github.com/visionmedia/haml.js) [(website)](http://haml.info/)
  - [haml-coffee](https://github.com/9elements/haml-coffee) [(website)](http://haml.info/)
  - [handlebars](https://github.com/wycats/handlebars.js/) [(website)](http://handlebarsjs.com/) (.hbs)
  - [hogan](https://github.com/twitter/hogan.js) [(website)](http://twitter.github.com/hogan.js/)
  - [jade](https://github.com/visionmedia/jade) [(website)](http://jade-lang.com/) (.jade)
  - [jazz](https://github.com/shinetech/jazz)
  - [jqtpl](https://github.com/kof/node-jqtpl) [(website)](https://github.com/kof/jqtpl)
  - [JUST](https://github.com/baryshev/just)
  - [liquor](https://github.com/chjj/liquor)
  - [lodash](https://github.com/bestiejs/lodash) [(website)](http://lodash.com/)
  - [mustache](https://github.com/janl/mustache.js)
  - [QEJS](https://github.com/jepso/QEJS)
  - [ractive](https://github.com/Rich-Harris/Ractive)
  - [swig](https://github.com/paularmstrong/swig) [(website)](http://paularmstrong.github.com/swig/)
  - [templayed](http://archan937.github.com/templayed.js/)
  - [toffee](https://github.com/malgorithms/toffee)
  - [underscore](https://github.com/documentcloud/underscore) [(website)](http://documentcloud.github.com/underscore/)
  - [walrus](https://github.com/jeremyruppel/walrus) [(website)](http://documentup.com/jeremyruppel/walrus/)
  - [whiskers](https://github.com/gsf/whiskers.js)



##### カスタムのビューエンジンを追加する

上記のリストに無いビューエンジンを追加するには[consolidate project](https://github.com/visionmedia/consolidate.js/blob/master/Readme.md#api) レポジトリをご確認ください。


<docmeta name="uniqueID" value="ViewEngines339501">
<docmeta name="displayName" value="View Engines">
