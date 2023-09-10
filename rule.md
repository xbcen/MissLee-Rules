# 以下是各个规则，可以自行选择使用
### 使用方法：找到相应应用
#### 第一个括号说明规则应写在哪个应用里，其他为注释
## 华为应用关闭更新（通用）
```
{"popup_rules":[{"id":"以后再说","action":"以后再说"}],"ltt_service":true}
```
---
## 华为主题广告（（华为）主题）
```
{"popup_rules":[{"id":"campaign_dialog_close_image","action":"campaign_dialog_close_image"},
{"id":"通知","action":"local_notice_push_colse"},
{"id":"iv_ad_close","action":"iv_ad_close"},
{"id":"广告","action":"pps_close_bottom"},
{"id":"不感兴趣","action":"不感兴趣"},
{"id":"pps_img_video_close","action":"pps_img_video_close"},
{"id":"download_pps_close","action":"download_pps_close"},
{"id":"iv_vip_close","action":"iv_vip_close"},
{"id":"pps_close","action":"pps_close"},
{"id":"tv_btn_uninterested","action":"tv_btn_uninterested"}],
"ltt_service":true}
```
---
## 华为安装器自动安装应用（华为应用市场）_（鸿蒙2.0）_
```
{"popup_rules":[
{"id":"正在查验","action":"正在查验","times":0},
{"id":"继续安装","action":"继续安装"},
{"id":"正在安装","action":"正在安装","times":0},
{"id":"打开","action":"完成"}],
"unite_popup_rules":true}
```
---
## 荣耀俱乐部自动签到（荣耀俱乐部）
```
{"popup_rules":[
{"id":"l_to_sign",
"action":"签到"}]}
```
---
## 微信关闭朋友圈/公众号部分广告
```
{"popup_rules":[
{"id":"hq","action":"hq"},
{"id":"jph","action":"jph"},
{"id":"直接关闭","action":"直接关闭"},
{"id":"jpa","action":"jpa"},
{"id":"container","action":"feedbackIcon"},{"id":"与我无关","action":"与我无关"},{"id":"不感兴趣","action":"不感兴趣"},{"id":"907,547,1010,650","action":"907,547,1010,650"}],"ltt_service":true}
```
---

