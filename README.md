# 明日方舟工具箱
### 一只灰猫

## 开始使用

目前已部署在Github Pages：[明日方舟工具箱 by 一只灰猫](https://aktools.graueneko.xyz/)

## 反馈

有任何建议、想法，或发现Bug，可以直接在本项目下提[Issue](https://github.com/graueneko/aktools/issues)。

如果你实现了新功能/改进可以合并到origin/master上，请发起[Pulll request](https://github.com/graueneko/aktools/pulls).

## 开发
```bash
git clone https://github.com/graueneko/aktools.git
cd aktools
npm i -s
ng serve -o
```
#### 注意事项
1. 开发请注意移动优先(Mobile First);
2. 尽管代码格式可能会随TSLint的配置不同发生变化，还请尽可能减少PR中未修改部分的代码变动;
3. 可以适量引入新图片、数据文件，但请勿加入过多、过大，以免国内网络访问过慢。

#### 参与开发您可能需要以下文档：
1. [Angular 8 中文文档](https://angular.cn/docs), or [Angular 8 Docs(en)](https://angular.io/docs)
2. [Blox Material Components](https://blox.src.zone/material/components)
3. [Angular Flex Layout](https://github.com/angular/flex-layout)


## 构建
```
ng build --prod --base-href "http[s]://*YOUR_URL*/"
```
可部署的site版本将生成在./dist/aktools目录下。
