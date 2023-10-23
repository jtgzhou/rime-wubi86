# rime-wubi86
五笔与拼音混输，默认关闭自动造词，并支持手动造词。

实现功能如下：
1、默认支持五笔拼音混输
2、默认关闭自动造词
3、手动造词分隔符`（Esc键与Tab键中间的那个键）
4、候选词根据最近输入自动调频
5、默认候选词为10个，默认字体为16号→均可调
6、默认四码唯一自动上屏
7、用；和’选第二重码与第三重码
8、用户词库wubi86_user.dict.yaml可以自行添加
9、默认使用左右Shift键和左右Ctrl键来切换中英文


使用方法
1、安装Rime
2、将如下6个文件拷贝至C:\Users\Administrator\AppData\Roaming\Rime
  pinyin.dict.yaml
  pinyin.schema.yaml
  wubi86.custom.yaml
  wubi86.dict.yaml
  wubi86.schema.yaml
  wubi86_user.dict.yaml
3、将上条目录下的installation.yaml文件末尾添加如下两行
installation_id: T20
sync_dir: D:\NAS\sw\Rime\Sync

其中T20为电脑名，可以自定义

4、在任务栏右键点击Rime输入法图标进行重新部署
5、输入法设定，选择本输入法（五笔拼音By芮轩）
