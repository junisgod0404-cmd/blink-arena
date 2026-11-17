# BLINK // ARENA — 3 MODES

## 시작
1. Node.js LTS 설치
2. 이 폴더에서 CMD 열기
3. `npm install`
4. `npm start`
5. http://localhost:3000 접속

## 게임 모드
- SOLO SURVIVAL: 1인 플레이 (다른 사람 필요 없음)
- CO-OP SURVIVAL: 방 코드로 2인 협동
- 1 VS 1 DUEL: 방 코드로 2인 대전

## PC / 모바일
PC: WASD/방향키 이동, Q 또는 클릭 공격, Space 대시, E 패링
모바일: 가상 조이스틱, 화면 터치 조준, 액션 버튼

## 인터넷 공개
localhost 주소는 다른 인터넷에서 접속할 수 없습니다.
친구에게 QR로 공유하려면 Node.js + WebSocket 지원 호스팅에 프로젝트 전체를 배포해야 합니다.
예: Render Web Service 또는 Railway. Start command: npm start, Build command: npm install.
배포한 HTTPS 주소에서 방을 만들고 QR 버튼을 누르세요.

## 주의
- 서버가 꺼지면 방은 사라집니다.
- DUEL 승수는 leaderboard.json에 저장됩니다. 호스팅의 임시 디스크에서는 재배포/재시작 때 소실될 수 있습니다.
- 현재는 과제용 프로토타입으로 닉네임 인증, 치트 방지, 네트워크 지연 보정이 완전하지 않습니다.
