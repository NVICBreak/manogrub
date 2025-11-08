# 魔女引导 - 魔裁风格的GRUB主题

> 本主题为 魔法少女的魔女审判（魔法少女ノ魔女裁判）的二次创作
> 
> 我直接使用并细微修改了游戏内原素材，如果这侵犯了你的版权，请联系我！十分抱歉！
> 
> 原作 Re,AER.

## 注意

**魔女引导**仅为 1080P 分辨率设计。

## 预览

<img src="/pics/example.png" width="50%"> 

（因为无法在GRUB内截图，因此预览图使用 Photoshop 制作，且可能与实际情况有所出入）

## 安装方法

1. 下载并解压

2. 将解压得到的文件夹复制到主题文件夹内 `sudo cp -r manogrub /usr/share/grub/themes`

3. 编辑配置文件 `sudo vim /etc/default/grub`

4. 在配置文件中添加主题路径 `GRUB_THEME="/usr/share/grub/themes/manogrub/theme.txt"`

5. 刷新GRUB配置 `sudo grub-mkconfig -o /boot/grub/grub.cfg`

6. 重启电脑

## 其它...

这是我首次独立制作 GRUB 主题，若有不妥当之处还请不吝赐教！非常感谢！
