# 오픈소스 SW개론 과제 : top, ps, jobs, kill 명령어 조사 
### 1. top
---
>top 명령어란? : 실시간으로 CPU 사용률을 체크해주는 도구


>top 사용 화면


![1](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/7c2f0a12-c34c-46d2-bd2c-3923aa478564)


#### 간략하게 설명하면


- ```03:47:15``` > 현재 서버 시간


- ```1:115``` > uptime(켜져있는 시간)

  
- ```(숫자) user``` > 접속중인 유저 세션 수

  
- ```load average``` > 5분,15분,30분 단위로 실행/대기 중인 프로세스 수를 나타낸다.
  

#### top 명령어는 실행 후 옵션이 많이 존재하는데 몇 개만 보면


```숫자 1``` 입력 시 > CPU Core별로 사용량을 보여준다. 


![2](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/7ab040c2-b8e6-4dcc-8c5c-b2bc0540b2da)


```a``` 입력 시 > 메모리 사용량에 따라 정렬한다.
**1,2,3,4 순서로 정렬된 걸 볼 수 있다.**


![8](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/e5592472-2e2d-4915-82f0-d4b9be53fd24)


### 2. ps
---
>ps 명령어란? : 현재 실행중인 프로세스 목록을 보여주는 명령어


>ps 사용 화면


![3](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/3557684f-b2c0-4b8d-a523-5e3e3e824bd7)


#### 간략하게 첫 줄 단어들의 의미를 설명하면


- ```PID``` > 프로세스 ID


- ```TTY``` > 프로세스의 제어 터미널 이름

  
- ```TIME``` > 프로세서의 누적 CPU 시간

  
- ```CMD``` > 프로세스를 시작하는 데 사용된 명령의 이름

#### ```ps (option)```으로 사용되는 여러 옵션이 존재하나 그 중 하나만 보면
- ```ps -l``` 입력 시 > 긴 포맷으로 보여준다.


![4](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/cce827f0-6863-4841-baf8-8dbcac169ba7)


### 3. jobs
---
>jobs 명령어란? : 작업의 상태를 표시하는 명령어


**jobs를 입력했을 때 실행중인 작업이 없다면 아무것도 출력되지 않는다.**

>jobs 사용 화면


![5](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/b342097f-a6de-4169-b6b3-ca638eb5c722)


#### 설명


- ```Running``` > 프로세스의 상태를 나타내는 것으로 현재 실행중인 상태이다. 


- ```sleep 100 &``` > 어떤 명령어를 실행했는지 보여준다.


#### ```jobs (options) (job)```으로 사용되는 여러 옵션이 존재하나 그 중 하나만 보면
- ```jobs -p``` 입력 시 > 잡의 프로세스 ID만 출력한다. 


![6](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/e6bfcfa2-4723-43fe-8427-f80c9fc747cd)


### 4. kill
---
>kill 명령어란? : 지정된 프로세스 또는 프로세스 그룹에 신호를 보내 신호에 따라 작동하도록 한다.


**그냥 kill를 입력했을 때는 실행이 되지 않는다. kill은 보낼 수 있는 신호가 따로 있다.**


>```kill -l``` 사용 화면(사용 가능한 신호 목록을 가져온다.)


![7](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/807fabef-d3e9-4327-903e-51437a1e83c6)
