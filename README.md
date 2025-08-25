# 42 Cub3D

## 개요
C 언어와 MiniLibX를 활용하여 구현한 **3D 레이캐스팅 게임** 프로젝트입니다.  
벽, 바닥, 천장을 표현하고 플레이어 이동 및 충돌 판정을 처리하며, `Wolfenstein 3D`에서 영감을 받은 게임 구조를 갖고 있습니다.

## 기능
- 레이캐스팅을 통한 3D 화면 렌더링
- 키보드 입력에 따른 이동 및 회전
- 충돌 판정 (벽 통과 방지)
- 맵 파일(`.cub`)을 읽어 게임 맵 구성
- 에러 처리 및 잘못된 입력 방어

## 사용법
```bash
# 컴파일
make

# 실행 예시
./cub3D map.cub
```

## 실행화면
<img width="1920" height="1045" alt="image" src="https://github.com/user-attachments/assets/7518759f-33dc-4d54-9b7f-9476a0f20dee" />
