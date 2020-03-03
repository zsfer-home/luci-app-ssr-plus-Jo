
# luci-app-ssr-plus

This is a backup repoistory of luci-app-ssr-plus from Lean's OpenWrt project package.

Lean's OpenWrt source:

<https://github.com/coolsnowwolf/lede/>

Source from tree: 2915c44a11ca0ee40b51ff5d9c18a0da1951e170

Lean's luci-app-ssr-plus source (history):

<https://github.com/coolsnowwolf/lede/tree/2915c44a11ca0ee40b51ff5d9c18a0da1951e170/package/lean/luci-app-ssr-plus>

# luci-app-ssr-plus-lean

## 说明
   源码来源：https://github.com/coolsnowwolf

 
## 此为原版ssr-plus修改服务器列表为图标切换/图标检测功能/V2ray分流

#### My other project
      
theme : https://github.com/Leo-Jo-My/luci-theme-opentomato

theme : https://github.com/Leo-Jo-My/luci-theme-opentomcat

theme : https://github.com/Leo-Jo-My/luci-theme-Butterfly

### 请配合以上主题使用 兼容所有魔改Argon主题

## 使用方法
```Brach
    #下载源码
    
    git clone -b lean  https://github.com/Leo-Jo-My/luci-app-ssr-plus-Jo package/luci-app-ssr-plus-Jo
 
 
    make menuconfig
    #编译
    make package/luci-app-ssr-plus-lean/{clean,compile} V=s
    


