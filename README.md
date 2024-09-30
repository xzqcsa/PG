# PG本地包（Sync From Telegram）

## 同步更新在线接口
选择主页可以查看当前PG包版本  
在线接口已经默认集成了tgsearch的在线服务器，无需任何tg配置  
使用自己的本地包可以填写tgsearch服务器地址：http://tg.seczh.com
```
http://www.xueximeng.com/p/jsm.json
```

## PG包下载地址
```bash
https://raw.yzuu.cf/fish2018/PG/main/pg.20240930-1307.zip
https://raw.nuaa.cf/fish2018/PG/main/pg.20240930-1307.zip
https://raw.kkgithub.com/fish2018/PG/main/pg.20240930-1307.zip
https://ghp.ci/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://gitdl.cn/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://gh.con.sh/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://ghproxy.net/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://github.moeyy.xyz/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://gh-proxy.com/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://ghproxy.cc/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://gh.llkk.cc/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://gh.ddlc.top/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
https://gh-proxy.llyke.com/https://raw.githubusercontent.com/fish2018/PG/main/pg.20240930-1307.zip
```

## pg包今日更新内容
PG包[README.txt](http://www.xueximeng.com/p/README.txt)  
```text
【对不起，我是阿里不限速网盘资源全秒播：https://t.me/pandagroovechat 阿里,UC,夸克使用本zip包不限速，阿里原画不需要svip也不用三方权益包，播放阿里内容不需要115账号秒传也不需要115VIP会员，115的分享内容无需付费即可欣赏，115分享大包和阿里分享大包不用建索引全部秒搜，UC原画不需要会员，夸克原画非会员3G以内的视频随意看，88VIP80G以内的视频随便看。所有网盘全自动删除转存垃圾文件，不限次数。所有网盘资源3秒起播让等待归零。可能是地球上唯一一个可以流畅在线播放ISO原盘的zip（注：使用外部播放器播放原盘ISO需要在任务列表中把影视锁定不被杀掉后台才能稳定播放）。注意：不支持仅使用jar，必须zip完整解压使用。网盘原画仅支持原版的影视、OK影视、EasyBox。對本zip内的核心jar的魔改或縫合都會導致網盤原畫不可播放。多个播放器或多次外挂本zip情况下，需要只保留一个播放器或1个外挂运行，其他的要主动杀掉，否则可能出现网盘播放异常】

今日更新内容：(更多内容阅读zip内的README.txt)
1.全新升级tgsearch，使用了新的api，支持群组内容全搜索（不限于最近1000条），并同时支持了最近1000条的详细搜索。多个群组也是10秒内返回结果，内容丰富度大大提高。除首次外，其他时候搜索都是瞬间返回结果。因为使用了新的api，因此需要重新获取session。
2.优化TG网盘Local免登录搜索结果集，显示资源更新时间。
3.修复tgsearch缓存刷新问题。增加超时控制防止卡死。因为使用了异步更新技术，所以搜索后的第一波结果数量不多，但等几秒在影视搜索结果的“TG搜索|网盘”这个分类里上滑刷新就会触发接收更多结果。修复不设置代理时无法搜索问题。修复空代理问题。增加运行提示。
```

## tgsearch包下载地址
```shell
https://raw.yzuu.cf/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://raw.nuaa.cf/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://raw.kkgithub.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://ghp.ci/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://gitdl.cn/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://gh.con.sh/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://ghproxy.net/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://github.moeyy.xyz/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://gh-proxy.com/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://ghproxy.cc/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://gh.llkk.cc/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://gh.ddlc.top/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
https://gh-proxy.llyke.com/https://raw.githubusercontent.com/fish2018/PG/main/tgsearchpack.20240930-1308.zip
```

## tgsearch包今日更新内容
```yaml
tgsearch多平台独立运行文件，使用./tgsearch
-h可以看帮助，也支持环境变量赋值（防止被坏人偷窥hash），具体环境变量分别是API_ID,API_HASH,STRINGSESSION,API_PROXY。
今日更新：使用全新api和全新的逻辑，双引擎异步+并发加载搜索结果，所有群组内容皆可搜（不限于最近1000条）无论多少群组都是5秒出结果，二次搜索还能提高搜索丰富度。注意：因为使用了新的api，因此要删掉原来的session，重新获取一次session，比之前长好多。修复缓存更新问题。修复不设置代理时无法搜素问题。修复空代理问题。增加运行提示。
```
