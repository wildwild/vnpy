# vn.ctp

### ���
CTP��̨API�ӿڵ�Python��װ������pyscriptĿ¼�µĽű��Զ�����ͷ�ļ����ɷ�װ����ģ�飬�ṩԭ��C++ API�е�ȫ�����ܡ�


### Ŀ¼˵��
* vnctpmd: ����API
* vnctptd: ����API
* pyscript: �Զ���װ�ű�
* ctpapi��C++ API�ļ�

### ʹ��CMake����

**��������**

* ���鰲װ�������λ���ϱ���һ�£�����ȫ����װ32λ��ͬʱ����32λ��

* cmake:��װ���°汾��cmake,�������ñ��뻷��

* [Boost1.57.0](http://sourceforge.net/projects/boost/files/boost/1.57.0/)�⣺����ķ������Բο�[Boost Getting Started](http://www.boost.org/doc/libs/1_58_0/more/getting_started/)���½ǵ�����

* ���û���������eg: BOOST_ROOT = C:\boost_1_57_0

* ����32λ�⻹��64λ������ѡ��

* ��Ҫ����boost python, thread, system, chrono, date_time��5���⣺������ȫ��������˷Ѵ���ʱ���Ӳ�̿ռ䡣

* boost python�Ķ�̬��64bits���ܱ��벻�ɹ������ѡ��address-model=64�����߱��뾲̬��

* [Anaconda1.9.2](http://repo.continuum.io/archive/index.html): ������ذ���Python���а�

* ���빤�ߣ�windows��ѡ��visual studio 2013��linux��ʹ��g++��

Linux: (Debian jessie)

* apt-get install build-essential

* apt-get install libboost-all-dev

* apt-get install python-dev

* apt-get install cmake

* ����ctp api tar��������v6.3.5_20150803_tradeapi_linux64.tar��������ctp api so�ļ�����

* thostmduserapi.so --> libthostmduserapi.so

* thosttraderapi.so --> libthosttraderapi.so


**�������**

* ��vn.ctpĿ¼���½��ļ��У�������Ϊbuild, ����������ʱ�ļ������ļ�

* �������й������룺cmake-gui .. ���cmake���ý���

* ���configure��

* ���generate�����û�д��������óɹ�

* ����buildĿ¼��˫��vn_ctp_api.sln�򿪽������

* ������밴ť,�������release��

**Linux: (Debian jessie)**

* ��ǰĿ¼����build.sh����ɱ���


### API�汾
���ڣ�2015-08-04

���ƣ�fsopt_traderapi

������������ȨAPI  

���ӣ�[http://www.sfit.com.cn/5_2_DocumentDown.htm](http://www.sfit.com.cn/5_2_DocumentDown.htm)

˵����ctpapi�ļ����µ���Windows��32λ�汾�������ļ���x64_linux�е���Linux��64λ�汾
