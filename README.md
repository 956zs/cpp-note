# 113-1 彈性課程學習 資訊二乙 21 張家笛
教材: [程式設計實習 陳愷柔](https://hackmd.io/@iKemLyBDTx-6CjTw2un6jQ/r1-Bck33A)

## (一)我的第一個C++程式
### 課後練習
1.cout練習
```
春眠不覺曉，處處聞啼鳥
夜來風雨聲，花落知多少
```
**★程式碼:**
```cpp=
#include <iostream>
using namespace std;

int main()
{
    cout << "春眠不覺曉，處處聞啼鳥\n";
    cout << "夜來風雨聲，花落知多少\n";
    return 0;
}
```
**☆執行畫面(請貼上截圖)**:
![image](https://hackmd.io/_uploads/Sk23smjbyg.png)

2.cout練習
```
*
**
***
****
*****
```
**★程式碼:**
```cpp=
#include <iostream>
using namespace std;

int main()
{
    string s;
    s = "*";
    for (int i = 0; i < 5; i++)
    {
        cout << s << "\n";
        s += "*";
    }
    return 0;
}
```
**☆執行畫面(請貼上截圖)**:
![image](https://hackmd.io/_uploads/rkHjimjbJg.png)


3.請利用"cin"與"cout"完成以下程式:

**★補充-資料型態說明:**
1. `int`: 整數型態
2. `string`: 字串型態
```
請輸入你的座號:99
請輸入你的姓名:王曉明
請輸入你的生日:900505
請輸入你的興趣:唱歌

嗨!99號王曉明您好，
您的生日是900505，興趣是唱歌。
很高興認識您。
```
**★程式碼:**
```cpp=
#include <iostream>
using namespace std;

int main()
{
    string setnumber, name, birthday, hobby;

    cout << "請輸入你的座號:";
    cin >> setnumber;
    cout << "請輸入你的姓名:";
    cin >> name;
    cout << "請輸入你的生日:";
    cin >> birthday;
    cout << "請輸入你的興趣:";
    cin >> hobby;

    cout << "\n嗨!" + setnumber + "號" + name + "您好，\n您的生日是" + birthday + "，興趣是" + hobby + "。\n很高興認識您。";

    return 0;
}
```
**☆執行畫面(請貼上截圖)**:
![image](https://hackmd.io/_uploads/SkcFsQsZ1g.png)


### 進階練習(加分題，同學有空再做)

1.輸入並顯示有效期限
```
有效期限 西元年分為:2024
有效期限 月份為:9
有效期限 日期為:6
本項產品的有效日期為:西元2024年9月6日
```
**★程式碼:**
```cpp=
#include <iostream>
using namespace std;

int main()
{
    string YYYY, MM, DD;
    cout << "有效期限 西元年分為:";
    cin >> YYYY;
    cout << "有效期限 月份為:";
    cin >> MM;
    cout << "有效期限 日期為:";
    cin >> DD;
    cout << "本項產品的有效日期為:西元" << YYYY << "年" << MM << "月" << DD << "日";
    return 0;
}
```
**☆執行畫面(請貼上截圖)**:
![image](https://hackmd.io/_uploads/H1l4s7ob1x.png)


2.利用空白隔開年月日
```
有效期限年月日(以空白隔開年月日):2024 9 9
本項產品的有效日期為:西元2024年9月9日
```
**★程式碼:**
```cpp=
#include <iostream>
using namespace std;

int main()
{
    string YYYY, MM, DD;
    cout << "有效期限年月日(以空白隔開年月日):";
    cin >> YYYY >> MM >> DD;
    cout << "本項產品的有效日期為:西元" << YYYY << "年" << MM << "月" << DD << "日";
    return 0;
}
```
**☆執行畫面(請貼上截圖)**:
![image](https://hackmd.io/_uploads/SklgSjXsZJe.png)


### 11/18 心得感想(100字): 
這次選修這門課其實是因為選課系統的意外，雖然這是去年的內容，但我發現很多基礎的東西還記得，學起來不會太困難。透過課程中的程式設計實習，讓我重新復習了C++語法，也發現自己對程式設計有更多的興趣。這段時間的學習讓我更加有信心繼續深入程式設計，期待能學到更多。