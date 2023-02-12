# `TinyCoreLinux`-`Config`

------

<div align=center>

[![Security Status](https://s.murphysec.com/badge/jidro/TinyCoreLinux-Config.svg)](https://www.murphysec.com/p/jidro/TinyCoreLinux-Config)

</div>

------

## 中文说明

这我自用的简单`TinyCoreLinux`配置文件    </br>

- `.Xdefault`(隐藏文件)导出路径为`~/`，此文件是`Aterm`终端的配置文件    </br>
- `opt`（文件夹）导出路径为根目录（`/`），    </br>
  - `bootlocal.sh` - 开机启动项、    </br>
  - `bootsync.sh` - 开机启动项、    </br>
  - `tcemirror` - 软件源地址、    </br>
  - `tcemirror.bak` - 备用软件源地址、    </br>
  - `background`文件夹 - 壁纸文件夹、    </br>
  - `shutdown.sh` - 关机项目及配置    </br>

请按照此路径返还    </br>

> `tcemirror`和`tcemirror.bak`这两个都是国内软件源地址。    </br>

我的修改：    </br>

- ① `bootlocal.sh`中添加了`tce=sda1`命令使得软件安装在磁盘而不是内存上。    </br>
- ② 终端颜色、文字、复制粘贴。    </br>

因为我还是新手，目前仅了解这些。    </br>

> 此为本人学习使用。     </br>
> 
> 由此提供对您的网站或计算机造成严重后果的本站概不负责。    </br>
> 
> 此为纯属个人学习使用，禁止任何机构及个人将此系统作为商业用途！    </br>
> 
> 禁止修改并盗用他人名义在网上传播！    </br>
> 
> 请在体验试用24小时之内删除销毁！    </br>
> 
> 若同意以上条款，方可对此进行下载使用！    </br>
> 
> 若已下载此中任何，即视为同意以上条款！    </br>
> 
> 若有侵犯行为，请联系本人删除。    </br>
> 
> 此仅为个人学习测试使用，请在下载后24小时内删除，不得用于任何商业用途，否则后果自负！    </br>

## English description：

This is my simple TinyCoreLinux configuration file for my own use        </br>

- `.Xdefault` (hidden file) export path is `~/`, this file is the configuration file of Aterm terminal         </br>
- The export path of `opt` (folder) is the root directory (`/`), and the files inside are `bootlocal.sh` (startup item), `bootsync.sh` (startup item), `tcemirror` (software source address), `tcemirror.bak` (alternative software) Source address), background folder (wallpaper folder), `shutdown.sh` (shutdown project and configuration)        </br>

Please follow this path to return    </br>

> Both tcemirror and `tcemirror.bak` are domestic software source addresses.    </br>

My modification:        </br>

- 1. The `tce=sda1` command has been added to `bootlocal.sh` so that the software is installed on the disk instead of the memory.        </br>
- 2. Terminal color, text, copy and paste.        </br>

Because I am still a novice, I only understand these at the moment.    </br>

> This is my study and use.    </br>
> 
> This site is not responsible for any serious consequences caused to your website or computer.    </br>
> 
> This is purely personal learning use, any organization or individual is prohibited from using this system for commercial purposes!    </br>
> 
> It is forbidden to modify and pirate the name of others to spread on the Internet!    </br>
> 
> Please delete and destroy within 24 hours of the trial trial!   </br>
> 
> If you agree to the above terms, you can download and use it!    </br>
> 
> If you have downloaded any of these, you are deemed to agree to the above terms!    </br>
> 
> If there is any violation, please contact me to delete it.    </br>
> 
> This is only for personal learning and testing.     </br>
> 
> Please delete it within 24 hours after downloading.     </br>
> 
> It must not be used for any commercial purposes, otherwise you will be responsible for the consequences!    </br>
