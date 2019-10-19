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

<br>

<br>
