#### ˵��

* ���������ͬ���������£��ʺ�һ�����ص�packageĿ¼�£�����openwrt����


* ��λL����ﶼɾ����ĳ�������Ϊ���˹���passwall������һ��������


- [passwall�������������ӣ�ע�⣡��openwrt����leanԴ���±���passwall��Ҫ���ش�������](https://github.com/kenzok8/small.git)
 

1�� lede/package$������ ����openwrt/package$������

```bash
 git clone https://github.com/tianku2020/my-openwrt-package.git
```
 2�� �������������뵽 openwrt ��ledeԴ���Ŀ¼feeds.conf.default�ļ�
```bash
 src-git tianku https://github.com/tianku2020/my-openwrt-package.git
```
 3�� passwall����
 ```bash
 src-git small https://github.com/kenzok8/small
 ```
 
- openwrt �̼������Զ������������
- luci-app-openclash       ------------------openclashͼ��         
- luci-app-advancedsetting ------------------ϵͳ�߼�����
- luci-theme-atmaterial    ------------------atmaterial ����һ���⣨����18.06��     
- luci-app-aliddns         ------------------������ddns
- luci-theme-argon-dark-new------------------����19.07��18.06������
- luci-app-eqos            ------------------��IP��ַ����
- luci-app-gost            ------------------���ε�https����
- luci-app-adguardhome     ------------------ȥ��� 
- luci-app-smartdns        ------------------smartdns����Ⱦ
- luci-app-passwall        ------------------Lienol���� 
- luci-theme-argon_new     ------------------����19.07��18.06������
- luci-app-ssr-plus        ------------------Lean���� 
- luci-theme-opentomcat    ------------------�޸���������������18.06��  
- luci-theme-opentomato    ------------------�޸���������������18.06��
#### ע��

* Lean������޸�Դ����������䣡



![��������](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-9.jpg)
![��������](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-10.jpg)
![��������](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-11.jpg)
![���ں�����](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-5.jpg)
![���ں�����](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-6.jpg)
![���ں�����](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-7.jpg)
![���ں�����](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-8.jpg)
![Ĩ��������](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-12.jpg)
![Ĩ��������](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-13.jpg)
![Ĩ��������](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-14.jpg)
![argon����](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-1.jpg)
![argon����](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-2.jpg)
![argon����](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-3.jpg)
![argon����](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/sshot-4.jpg)
* �޸�opentomato ��opentomcat�޸���������Ч��bug
![�޸�tomto�����޸���������bug](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/%E5%B0%8F%E7%8C%AA%E5%AE%B6-719.png)
![�޸�tomto�����޸���������bug](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/%E5%B0%8F%E7%8C%AA%E5%AE%B6-722.png)
![�޸�cat�����޸���������bug](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/%E5%B0%8F%E7%8C%AA%E5%AE%B6-720.png)
![�޸�cat�����޸���������bug](https://raw.githubusercontent.com/kenzok8/openwrt-packages/master/screenshot/%E5%B0%8F%E7%8C%AA%E5%AE%B6-721.png)

