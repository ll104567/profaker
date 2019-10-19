#profake
<br>
python生成随机字符、中英文用户名、手机号、身份证等
<br>

<br>
test ok : python 3.7
<br>
Usage:
<br>

<br>
from fake_modules.utils.tools import * 
<br>
from fake_modules.fake_email import email
<br>
from fake_modules.fake_id import make_id,check_id
<br>
from fake_modules.fake_ip import ip
<br>
from fake_modules.fake_name import name
<br>
from fake_modules.fake_number import number
<br>
from fake_modules.fake_phone import phone
<br>

<br>
├── fake_modules
<br>
│   ├── fake_email.py
<br>
│   ├── fake_id.py
<br>
│   ├── fake_ip.py
<br>
│   ├── fake_name.py
<br>
│   ├── fake_number.py
<br>
│   ├── fake_phone.py
<br>
│   ├── __init__.py
<br>
│   └── utils
<br>
│       ├── __init__.py
<br>
│       └── tools.py
<br>
├── __init__.py
<br>
└── README.md
<br>

<br>
2 directories, 11 files
<br>
In [9]: from fake_modules.fake_email import email
<br>

<br>
In [10]: email()
<br>
Out[10]: '340845548@qq.com'
<br>

<br>
In [11]: email()
<br>
Out[11]: '889653208@qq.com'
<br>

<br>
In [12]: email()
<br>
Out[12]: '121947281@qq.com'
<br>

<br>
In [13]: email()
<br>
Out[13]: '411840113@qq.com'
<br>

<br>
In [14]: email()
<br>
Out[14]: '707213122@qq.com'
<br>

<br>
In [15]: email()
<br>
Out[15]: 'fzzklrbvc@yahoo.com.cn'
<br>

<br>
In [16]: email()
<br>
Out[16]: '539740494@qq.com'
<br>

<br>
In [17]: email(10)
<br>
Out[17]: 
<br>
['jbqdaovgp@sina.com',
<br>
 'lxvecf@sohu.com',
<br>
 'okfvdnq@126.com',
<br>
 '433728638@qq.com',
<br>
 '315687424@qq.com',
<br>
 '432175178@qq.com',
<br>
 '750580241@qq.com',
<br>
 'cgahsu@yahoo.com',
<br>
 'smoipajwew@gmail.com',
<br>
 'fedmraxkys@126.com']
<br>

In [1]: from fake_modules.fake_id import id
<br>

<br>
In [2]: id()
<br>
Out[2]: '518254196205188444'
<br>

<br>
In [3]: id()
<br>
Out[3]: '359715198008029965'
<br>

<br>
In [4]: id(10)
<br>
Out[4]:
<br>
['321806196312173694',
<br>
 '325932199809153205',
<br>
 '603350194809203068',
<br>
 '721020194703228479',
<br>
 '408540195807079171',
<br>
 '479377198912048480',
<br>
 '700271197004289416',
<br>
 '983564196008140902',
<br>
 '853839199308245145',
<br>
 '178939195809109651']
<br>

In [5]: from fake_modules.fake_ip import ip
<br>

<br>
In [6]: ip()
<br>
Out[6]: '127.208.173.224'
<br>

<br>
In [7]: ip()
<br>
Out[7]: '239.119.177.244'
<br>

<br>
In [8]: ip()
<br>
Out[8]: '221.184.242.202'
<br>

<br>
In [9]: ip(10)
<br>
Out[9]:
<br>
['110.31.139.49',
<br>
 '149.37.87.15',
<br>
 '190.93.212.96',
<br>
 '8.182.16.145',
<br>
 '114.80.25.200',
<br>
 '149.233.90.7',
<br>
 '121.159.210.142',
<br>
 '194.199.8.28',
<br>
 '194.234.168.17',
<br>
 '184.82.240.139']
<br>

In [1]: from fake_modules.fake_name import name
<br>

<br>
In [2]: name()
<br>
Out[2]: '范泰'
<br>

<br>
In [3]: name()
<br>
Out[3]: '邹斌'
<br>

<br>
In [4]: name(10)
<br>
Out[4]: ['于妍', '何盛', '廉发', '邬雅', '祁园', '马贵', '齐妹', '姚辰', '王悦', '贝荔']
<br>

