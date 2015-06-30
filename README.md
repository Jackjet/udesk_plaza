
反馈标签的使用方法
---------------------------

将此代码粘贴在每个网页上您想要使反馈标签出现的地方

您应将此代码直接插入 </body> 标记符前，而不是在 <head> 中，这一点很重要

以下代码可放置在您的网站、网络 app，或您的在线商店中的任何页面上。如果您对在何处或如何将此放置在网页上不确定，您应联系您的技术团队或网络管理员。如果您可以访问内容管理系统，通常您可以将此代码放在页脚模板中。


```html
<script type="text/javascript" src="https://udesk.github.io/udesk_plaza/feedback/udesk_feedback.js"></script>
<style type="text/css" media="screen, projection">
  @import url(https://udesk.github.io/udesk_plaza/feedback/udesk_feedback.css);
</style>
<script type="text/javascript">
  if ('undefined' !== typeof(UdeskFeedback)) {
    UdeskFeedback.init({
      url: 'https://你公司的二级域名.udesk.cn',
      mode: 'neither',
      color: 'purple',
      title: '反馈',
      position: 'right'
    });
  }
</script>
```
