# 说明

一个微信顶部的搜索导航条组件，内容与右边的胶囊按钮对齐。自带一个搜索图标。

## 使用

```
<nav-search-bar
  logoImg="../../assets/images/logo/my-music-logo-144.png"
  title="YT Music"
  bind:tap-search="onSeachTap"
>
```

`logoImg`: 导航栏最左边的logo图标，不传则不显示；

`title`: logo 旁边的文字描述，不传则不显示；

`bind:tap-search`: 点击搜索图标后会触发 `tap-search` 事件，可在它的事件响应中导航到新页面

完。