# sed
Q: 用sed插入行,行首有空格
A: `sed '3a \ 444'`
A: sed '3r '<(echo '444')

Q:原文`1111bbbb`, 输出为`1111\|systembbbb`
A:echo 1111bbbb|sed 's#1111#&\\|system#'
其中&代表匹配内容, #和/一样
