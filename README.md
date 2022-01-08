# NexT


## 一、 安装依赖

```shell
npm install
```

## 二、 hexo常用命令

```shell
# 清除生成的静态文件(每次修改过文章内容后需要清理原来的静态文件然后重新生成)
hexo clean
# 生成静态文件
hexo g
# 运行
hexo s
# 部署(部署前需要将自己的信息都配置好：github地址、社交地址、百度分析、评论系统、头像、作者等)
hexo d
```

## 三、 需要配置（按个人需求）

### 1. 项目根目录/_config.yml`

- `site`

  ```yml
  # 网站标题
  title: ***
  # 作者名
  author: ***
  ```

- `deploy`

  ```yml
  # github个人主页仓库地址
  repo: https://******.com
  ```

### 2. `themes/next/_config.yml`

- `avatar`

  ```yml
  # 侧边栏头像
  url: ***.jpg
  ```

- `social`

  ```yml
  # github地址
  GitHub: https://******.com || fab fa-github
  # 邮箱
  E-Mail: mailto:******@**.com || fa fa-envelope
  # 微博
  Weibo: https://******.com || fab fa-weibo
  ```

- `github_banner`

  ```yml
  # github地址
  permalink: https://******.com
  ```

  

- `changyan`（https://changyan.kuaizhan.com）

  ```yml
  # 评论系统(自己百度看配置方法)
  appid: ******
  appkey: ******
  ```

  

- `Baidu Analytics`（https://tongji.baidu.com）

  ```yml
  # 百度分析(自己百度看配置方法)
  baidu_analytics: ******
  ```
