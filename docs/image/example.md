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

<!-- 你的其他脚本 -->
<script src="/js/dist/autoload.js"></script>

<!-- ✅ 正确引入 Plyr CSS 和 JS -->
<link rel="stylesheet" href="https://cdn.plyr.io/3.6.12/plyr.css" />
<script src="https://cdn.plyr.io/3.6.12/plyr.js"></script>

<!-- ✅ 单独初始化 Plyr -->
<script>
  document.addEventListener('DOMContentLoaded', () => {
    console.log("Initializing Plyr...");
    const player = new Plyr('#player');
    
    // 如果你还有 Live2D 相关逻辑，也可以放这里
    updateWaifuStyle();
    setInterval(updateWaifuStyle, 1000);
  });
</script>