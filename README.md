
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |


| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |
| git status | List all new or modified files |


| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
| `git status` | List all *new or modified* files |


| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
| git status   | git status     | git status    |


| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |
| Backtick | `         |


| 左对齐  | 右对齐   | 居中对齐 |
|:-------|--------:|:-------:|
| 单元格1 | 单元格2 | 单元格3 |
| 单元格4 | 单元格5 | 单元格6 |
| 单元格7 | 单元格8 | 单元格9 |

<table>
  <tr>
    <td>Table</td>
  </tr>
  <tr>
    <td>Row</td>
  </tr>
</table>



| 年份 | GDP（亿元） | 增长率(%) |
| ---- | ---------- | -------- |
| 2022 | 未给出    |          |
| 2023 | 未给出    |          |
| 2024 | 一季度    | 10581.40 |
|      | 二季度    | 21791.30 |
| 注：以上数据来源于网络，由于搜索结果中并未提供2022年和2023年北京具体的GDP数据，因此无法列出确切的数值。如果需要详细了解这两年的具体GDP数据，建议查阅相关政府发布的统计年鉴或官方统计数据。 |




 Hello, World in Various Programming Languages

The "Hello, World" program is often the first program learned by programmers in various programming languages. It typically prints or displays the text "Hello, World" to the console or screen. Here's a compilation of the Hello, World programs in different languages:

| Language    | Code |
|||
| Assembly    | ```bash
bdos equ 0005H
; BDOS entry point
start:
mvi c,9
; BDOS function: output string
lxi d,msg$
; address of msg
call bdos
ret
;
msg$:
db 'Hello, world!'
end
start``` |
| COBOL      | ```bash
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.
PROCEDURE DIVISION.
DISPLAY Hello, World!
STOP RUN.``` |
| BASIC      | ```PRINT Hello, World!END``` |
| Fortran    | ```PROGRAM HelloWRITE (,) 'Hello, World!'STOP END``` |
| Pascal     | ```program HelloWorld(output);begin writeln('Hello, World!'); readln; end.``` |
| C          | ```main()puts("Hello, World!");``` |
| C++        | ```cpp
include <iostream>
using namespace std;

int main() 
cout << "Hello, World!" << endl;
return 0;
 ``` |
| Python     | ```python
print("Hello, World!")
``` |
| Java       | ```java
public class HelloWorld 
public static void main(String args) 
System.out.println("Hello, World!");


``` |
| JavaScript  | ```javascript
console.log("Hello, World!");
``` |
| PHP        | ```php
echo "Hello, World!";
``` |
| Swift      | ```swift
print("Hello, World!")
``` |
| Ruby       | ```ruby
puts "Hello, World!"
``` |
| Go         | ```go
package main

import "fmt"

func main() 
fmt.Println("Hello, World!")

``` |

These are just a few examples of the many programming languages available. Each language has its own syntax and features, but they all share the common goal of allowing programmers to create software solutions.  
















