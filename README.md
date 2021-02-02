# README

项目说明：

```
main:主应用（基座）
purehtml:纯html应用
react:react应用
vue:vue应用
```

项目运行：

分别进入四个应用文件夹，执行命令

```markdown
yarn

npm start
```

各应用对应的本地端口号：

```javascript
// 主应用:'//localhost:7099',

{
	name: 'react',
	entry: '//localhost:7102',
	container: '#subapp-viewport',
	loader,
	activeRule: '/react',
},
{
	name: 'vue',
	entry: '//localhost:7101',
	container: '#subapp-viewport',
	loader,
	activeRule: '/vue',
},
{
	name: 'purehtml',
	entry: '//localhost:7104',
	container: '#subapp-viewport',
	loader,
	activeRule: '/purehtml',
},
```

打开：`http://localhost:7099` 即可访问本地创建的微前端应用