# 给开发者
开发者您好  
现在目录结构大变样，请按照[我](./name/name.md#me)写好的md文件进行编写  
不要使用老式的数字锚点，改为使用文字锚点如**我** 现在为./name/name.md#me  
编辑模式下花括号（大括号{}）中的内容就是锚点
以下是在各个目录引用name文件的方法   

| 目录        | 引用方案                                        |
|-----------|---------------------------------------------|
| docs(主目录) | `./name/name.md` 或 `./name/name_thing.md`   |
| name      | `name.md` 或 `name_thing.md`                 |
| thing     | `../name/name.md` 或 `../name/name_thing.md` |

以下是各个名词对应的锚点


| 名词       | 锚点       |
|----------|----------|
| 茕山羊      | #goat    |
| 我        | #me      |
| mdn      | #mdn     |
| 绿宝石      | #emerald |
| 维多利亚     | #wdly    |
| COVD19   | #codvi9  |
| 蜃涟       | #qsj     |
| 马步芳（非真实） | #creeper |
| 议会       | #meeting |
| mumu       | #mumu |
| 醉鸡王       | #linbiao |
| 卡尔·李卜克内西   | #mickymomse |
| 红树原木    | #redwood  |
| 蜃涟      | #qsj |

##注意事项
202584 18:30 [我](name/name.md#mdn)闲的没事干，加了个评论功能，注意避开每个文件末尾的html标签

## 第三方组件许可证

- `https://unpkg.com/oh-my-live2d@latest` (来自 oh-my-live2d https://github.com/oh-my-live2d/oh-my-live2d?tab=MIT-1-ov-file)  
  - 许可证: MIT  
  - 原始许可证文本:  


>MIT License

>Copyright (c) 2022 oh-my-live2d and hacxy

>Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

>The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

- [live2d-widget](https://github.com/stevenjoezhang/live2d-widget?tab=GPL-3.0-1-ov-file)
  - 许可证GPL 3.0
  - 本项目基于 GNU General Public License v3.0 许可证发布，原始项目也使用 GPL-3.0。

  - 修改内容：
    - 添加了多模型配置设置
  - 原始许可证文本：[点我查看](https://github.com/stevenjoezhang/live2d-widget/blob/master/LICENSE)

<script src="/js/dist/autoload.js"></script>
 <script>
// 页面加载完成后开始定期执行
window.addEventListener('load', () => {
  console.log("Live2D waifu script loaded.");
  
  // 初始执行一次
  updateWaifuStyle();

  // 每隔 1 秒检查一次 modelId 是否发生变化（例如其他脚本修改了 localStorage）
  setInterval(() => {
    console.log("running");
    updateWaifuStyle();
  }, 1000);
});
  </script>
<div id="giscus"></div>
<script src="https://giscus.app/client.js"
        data-repo="nomdn/GoatBook-Source"
        data-repo-id="R_kgDOPXYjCw"
        data-category="General"
        data-category-id="DIC_kwDOPXYjC84Ctwim"
        data-mapping="title"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        crossorigin="anonymous"
        async>
</script>
