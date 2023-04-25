# CCProxy缓冲区溢出攻击

attack.py : 使用socket向CCProxy发送包含shellcode的溢出攻击代码

1.txt : 测量缓冲区所用的可分辨字符串

patternCreate.pl : 生成上述字符串

patternOffset.pl : 得到一段字符在整个串中的偏移

具体内容详见说明文档
