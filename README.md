## HERE: you must change the url in _config.yml first!
## HERE: you must change the url in _config.yml first!

这个仓库基本配置好了装有kira主题的Hexo静态网站，您可以使用这个仓库来进行测试

如果您想要基于这个仓库来个性化您的网站，只需要把这个仓库克隆，并参考[官方文档](https://kira.host/hexo/)修改_config.kira.yml和_config.yml即可

### 注意
1. 如果你打算使用gulp来加快渲染速度，可以在package.json添加下述代码（你在本地测试时需要确保有安装相关的插件来执行gulp，github：action的linux环境以及配置过了，这个不用担心）
  ```json
	"devDependencies": {
	  "gulp": "^4.0.2",
	  "gulp-minify-css": "^1.2.4",
	  "gulp-babel": "^8.0.0",
	  "gulp-uglify": "^3.0.2",
	  "gulp-htmlmin": "^5.0.1",
	  "gulp-htmlclean": "^2.7.22",
	  "gulp-imagemin": "^7.1.0",
	  "imagemin-jpegtran": "^7.0.0",
	  "imagemin-svgo": "^11.0.0",
	  "imagemin-gifsicle": "^7.0.0",
	  "imagemin-optipng": "^8.0.0"
	}

  ```

