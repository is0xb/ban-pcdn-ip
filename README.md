# ban-pcdn-ip


**20250405开始恢复更新，数据来源为本人的CDN异常刷量记录**

收集恶意刷取网站CDN流量的PCDN IP段清单。
一些PCDN的所有者已经将原先的BT流量来源切换为使用CDN的网站，导致许多站长面临大额的账单支出。



## ip清单
ipdb.txt文件，已经排序。

## main.py
用来对ipdb.txt进行排序和去重的脚本。
如果本机有python环境，建议添加地址段后，提交前执行main.py进行排序。如果本机没有python环境，当然也可以手工把地址添加到对应位置。
**若能把新地址段按照排序顺序增加到对应位置，最好不过了，这样我合并PR后也无需再排序。**

## 关于补充ip数据
如果有补充的地址，大家可以在 ipdb.txt 里直接增加 ip 段，然后提交上来，目前非常依赖用户贡献新的地址段。
### 要求
为避免误伤正常IP，大家提pr或者issue同时，需要提供自己CDN被刷的截图或者可靠来源链接，方便验证。


## 情况介绍部分链接

### v2ex
https://www.v2ex.com/t/1056361

https://www.v2ex.com/t/1055550

https://www.v2ex.com/t/1055838

https://www.v2ex.com/t/1055510

https://www.v2ex.com/t/1055422

https://www.v2ex.com/t/1052331

https://www.v2ex.com/t/1045318

### 多吉云公告
https://www.dogecloud.com/announcement/26

### 其他
https://linux.do/t/topic/169770
