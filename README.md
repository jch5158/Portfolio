# 구성

<br>

- 포트폴리오 : 정찬훈 게임 서버 포트폴리오.pdf

<br><br><br>

# 기술 블로그

<br>

- https://vanilla-tech.tistory.com/

<br><br><br>

# 구현 프로젝트

<br>

<동영상 웹 서비스 프로젝트 : Watching><br>
프로젝트 명 : Watching

<br>

프로젝트 개요 :

- "Watching" 프로젝트는 동영상 업로드, 시청, 좋아요, 구독, 댓글, 대댓글과 같은 컨텐츠를 즐길 수 있는 동영상 웹 서비스 프로젝트입니다.

<br>

개발환경 :

- OS : Ubuntu(WSL 사용)
- 백엔드 : express 프레임 워크
- 클라이언트 : pug, scss, JavaScript
- DB : MongoDB, Redis
- 배포 환경 : AWS EC2
- 클라우드 스토리지 : AWS S3

<br>

구현 목록 :

- 이메일 인증 회원 가입, OAuth
- 로그인 & Session 방식을 이용한 로그인 상태 유지 구현
- 회원 정보 수정 구현
- 채널 구독 구현
- 동영상 업로드 & 수정 & 삭제 구현
- 댓글, 대댓글 달기 & 좋아요 & 수정 & 삭제 구현
- 정규식을 통해 동영상 제목 또는 태그 검색 기능 구현
- 동영상 & 댓글 인피니티 스크롤 구현
- AWS 인증서를 이용한 https 구현
- 동영상 조회수 시스템 구현

<br><br><br>

<MMORPG 프로젝트 : GodDamnBug><br>
프로젝트 명 : GodDamnBug

<br>

프로젝트 개요 :

- "GodDamnBug" 프로젝트는 광활한 맵에서 몬스터를 찾아 사냥 및 재화를 수집할 수 있으며, 다른 유저들과 채팅을 통해 대화를 즐길 수 있는 MMORPG 게임 프로젝트입니다.

<br>

개발 환경 :

- OS : Windows
- 클라이언트 : Unity ( 클라이언트는 학원에서 제공 받았습니다. )
- 사용 언어 : C/C++
- 네트워크 통신 : NetServer/MMOServer 네트워크 엔진을 제작하여 클라이언트와 서버 그리고 서버와 서버간의 TCP 통신을 구현하였습니다.
- DB : MySQL, Redis

<br>

구현 목록 :

- 플레이어 이동, 단일 공격 & 범위 공격, 아이템 줍기, 휴식, 사망, 사망 후 재시작 구현
- 게임 내 채팅 구현
- 몬스터 이동 & 공격자 추적 & 공격 구현
- 게임 내 컨텐츠 결과를 비동기 I/O를 통해 DB에 저장 구현
- 로그인 서버로 유저 인증 및 임시 토큰을 발행하여 Redis에 저장 구현
- 모니터링 서버로 각 서버들의 리소스 및 컨텐츠 상태를 수집 및 DB에 저장 구현

<br><br><br>

<LockFree Algorithm 프로젝트><br>
프로젝트 명 : LockFree Algorithm

<br>

프로젝트 개요 :

- "LockFree Algorithm"은 멀티 쓰레드 환경에서 사용할 수 있는 스택, 큐 컨테이너를 개발하고 이를 기반으로 메모리 프리 리스트, 오브젝트 프리 리스트를 구현한 프로젝트입니다.

<br>

개발 환경 :

- OS : Windows
- 언어 : C/C++

<br>

구현 목록 :

- 멀티 쓰레드 환경에서 안전하게 사용할 수 있는 LockFree 스택, 큐 컨테이너 구현
- 메모리 할당 및 반환을 위한 LockFree 메모리 프리 리스트 구현
- 오브젝트 할당 및 반환을 위한 LockFree 오브젝트 프리 리스트 구현
- 각 컨테이너 및 프리 리스트의 성능 측정 및 비교 분석을 위한 프로파일러 구현

<br><br><br>

<A* & JPS 길 찾기 프로젝트><br>
프로젝트 명 : A* & JPS 길 찾기 프로젝트

<br>

프로젝트 개요 :

- "A\* & JPS 길 찾기 프로젝트"는 일정 크기의 노드로 구성된 맵에서 출발지에서 목적지까지 경로를 구하기 위해 구현한 프로젝트입니다.

<br>

개발 환경 :

- OS : Windows
- 언어 : C/C++

<br>

구현 목록:

- A\* 알고리즘을 이용한 경로 탐색 구현
- JPS(Jump Point Search) 알고리즘을 이용한 경로 탐색 구현
- WinAPI를 이용해 경로 탐색 시각화 구현
- 브레즌험 알고리즘을 이용해서 자연스러운 경로 구현
- A\*와 JPS 알고리즘의 성능 비교 분석 및 결과 도출
