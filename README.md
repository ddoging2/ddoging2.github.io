# 오픈소스 SW개론 과제 : top, ps, jobs, kill 명령어 조사 
### 1. top
---
>top 명령어란? : 실시간으로 CPU 사용률을 체크해주는 도구

>top 사용 화면

![1](https://github.com/ddoging2/ddoging2.github.io/assets/171368038/7c2f0a12-c34c-46d2-bd2c-3923aa478564)
#### 간략하게 첫줄만 설명하면
```

- 03:47:15 > 현재 서버 시간
- 1:115 > uptime(켜져있는 시간)
- 0 user > 유저
- load average > 현재 시스템이 얼마나 일을 하고 있는지 실행/대기 중인 프로세스 수를 나타낸다.

```

#### top 명령어는 실행 후 옵션이 많이 존재하는데 그 중 하나만 보면
- shift + p > CPU 사용률을 내림차순으로 보여준다.

