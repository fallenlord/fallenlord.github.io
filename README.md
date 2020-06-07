# Cooolin's Blog

## 编写

1. 启动Jekyll：`bundle exec jekyll serve`
2. 在`_posts`下新增文件，编写内容
3. 访问`http://localhost:4000`预览
4. `git commit` / `git push`

## 初次安装

根据[Jekyll](https://jekyllrb.com/)指示初始化并运行网站：

```sh
gem install bundler jekyll
jekyll new cooolin.com
cd cooolin.com
bundle exec jekyll serve
```

然后，由于使用的是[Clean Blog Jekyll](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll)主题，按照其上说明操作：

1. 在上一步创建的目录中，将`Gemfile`中主题替换为`"jekyll-theme-clean-blog"`
2. 执行 `bundle install` 进行安装
3. 修改 `_config.yml` 中的主题 `theme: jekyll-theme-clean-blog`
4. 运行 `bundle exec jekyll serve`

## 其他模板

- [huxpro](https://github.com/Huxpro/huxpro.github.io/blob/master/README.zh.md)

## Roadmap

- OpenCV
- 360°全景相机的算法实现
- 全局代理之Windows版
- 全局代理之MacOS版
- 全局代理之iOS版
- 全局代理之Android版
- 与Docker结合的DevOps实践
- DevOps之GitLab全攻略
- DevOps之阿里云
- DevOps之Google Cloud
- OpenCV从入门到放弃
- Flutter从入门到放弃
- docker/k8s



