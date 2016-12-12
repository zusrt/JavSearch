#javID-SearchTool

Find magnetlink and download cover image via javID

一个可以通过番号来下载封面和磁链的单线程小工具。



## Installation

```bash
$ git clone https://github.com/VegetableCat/javID-SearchTool
$ cd javID-SearchTool
$ pip install -r requirments.txt
$ python jav-download.py
```




## Usage

```bash
  Usage: python jav-download.py [options]

  Options:

    -h, --help                show help
	-a, --avcode              javID what you want to download
```


### Examples

```bash
# 下载番号为mum-238的影片
$ python downcode4javbus.py -a mum238
MUM-238 私の事を愛してくれる友達のお父さん。 141cmつるつる いろはめる
download cover image
5j6h_b done!
mum00238jp-1 done!
mum00238jp-2 done!
mum00238jp-3 done!
mum00238jp-4 done!
mum00238jp-5 done!
mum00238jp-6 done!
mum00238jp-7 done!
mum00238jp-8 done!
mum00238jp-9 done!
mum00238jp-10 done!
magnet:?xt=urn:btih:21BB8BB985441E2871B3E8676434EB733FA86003&dn=MUM-238 
2.06GB
magnet:?xt=urn:btih:96DF6A80477348E182769BE6484F28DDBFDEB482&dn=0703_MUM-238.avi 
2.04GB
magnet:?xt=urn:btih:6CEF2900746528D5B267495604BF201AC5014C03&dn=MUM-238.avi 
2.04GB
magnet:?xt=urn:btih:A9DAE855800D93EFD8880972F15421F4F4F76600&dn=MUM-238-AVI 
2.04GB
```
文件结构
```bash
$ tree
.
├── jav-download.py
├── library
│   └── MUM-238 私の事を愛してくれる友達のお父さん。 141cmつるつる いろはめる
│       ├── 5j6h_b.jpg
│       ├── mum00238jp-10.jpg
│       ├── mum00238jp-1.jpg
│       ├── mum00238jp-2.jpg
│       ├── mum00238jp-3.jpg
│       ├── mum00238jp-4.jpg
│       ├── mum00238jp-5.jpg
│       ├── mum00238jp-6.jpg
│       ├── mum00238jp-7.jpg
│       ├── mum00238jp-8.jpg
│       └── mum00238jp-9.jpg

```


## Notes
- 运行需要代理：xx-net socks5都可以
- 默认代理是ss的代理：127.0.0.1:1080 
- 封面和例图会放在运行目录下的library目录中

## Todo
- 将本地代理ip端口放到选项中，自定义选择
- magnet链接转换为种子，下载到对应目录中
- 滋滋telegram bot