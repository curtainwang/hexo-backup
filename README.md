#hexo-backup
hexo备份插件

#安装
	$ npm i hexo-backup --save
	
	

*可能需要自己rebuild一下execSync,使用`node-gyp rebuild`*
#配置 _config.yml
在_config.yml里面添加backup配置


示例
```yaml
# backup
backup:
  branch: hexo
  repo: git@gitcafe.com:magicdawn/magicdawn.git
```

#使用
```shell
hexo backup --init #初始化备份
hexo backup #备份操作
```

b -> backup的简写