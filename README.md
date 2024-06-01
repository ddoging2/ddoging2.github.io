# 오픈소스 SW개론 과제 : top, ps, jobs, kill 명령어 조사 
### 1. top
---
>top 명령어란? : 실시간으로 CPU 사용률을 체크해주는 도구


>top 사용 화면


![1](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/7c2f0a12-c34c-46d2-bd2c-3923aa478564)


#### ```간략하게 첫줄만 설명하면```


- 03:47:15 > 현재 서버 시간


- 1:115 > uptime(켜져있는 시간)

  
- (숫자) user > 접속중인 유저 세션 수

  
- load average > 5분,15분,30분 단위로 실행/대기 중인 프로세스 수를 나타낸다.
  

#### ```top 명령어는 실행 후 옵션이 많이 존재하는데 그 중 하나만 보면```


- 1 입력 시 > CPU Core별로 사용량을 보여준다. 


![2](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/7ab040c2-b8e6-4dcc-8c5c-b2bc0540b2da)


### 2. ps
---
>ps 명령어란? : 현재 실행중인 프로세스 목록을 보여주는 명령어


>ps 사용 화면


![3](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/3557684f-b2c0-4b8d-a523-5e3e3e824bd7)


#### ```간략하게 첫줄 단어들의 의미를 설명하면```


- PID > 프로세스 ID


- TTY > 프로세스의 제어 터미널 이름

  
- TIME > 프로세서의 누적 CPU 시간

  
- CMD > 프로세스를 시작하는 데 사용된 명령의 이름

#### ```ps (option)으로 사용되는 여러 옵션이 존재하나 그 중 하나만 보면```
- ps -l 입력 시 > 긴 포맷으로 보여준다.


![4](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/cce827f0-6863-4841-baf8-8dbcac169ba7)


### 3. jobs
---
>jobs 명령어란? : 작업의 상태를 표시하는 명령어
<span style="color:red">jobs를 입력했을 때 실행중인 작업이 없다면 아무것도 출력되지 않는다.</span>
<span style="color: #FF0000">빨강</span>
<span style="color: #0000FF">파랑</span>
<span style="color: #008000">초록</span>
<span style="color: #808080">회색</span>
<span style="color: #ffd33d">노랑</span>

>jobs 사용 화면


![3](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/3557684f-b2c0-4b8d-a523-5e3e3e824bd7)


#### ```간략하게 첫줄 단어들의 의미를 설명하면```


- PID > 프로세스 ID


- TTY > 프로세스의 제어 터미널 이름

  
- TIME > 프로세서의 누적 CPU 시간

  
- CMD > 프로세스를 시작하는 데 사용된 명령의 이름

#### ```ps (option)으로 사용되는 여러 옵션이 존재하나 그 중 하나만 보면```
- ps -l 입력 시 > 긴 포맷으로 보여준다.


![4](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/cce827f0-6863-4841-baf8-8dbcac169ba7)



