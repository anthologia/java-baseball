# 풀이 기록
## 생각 정리
이번에도 역시 먼저 작동하는 코드를 구현하는 것을 우선시하기로 결정했다.

그러나 클린코드를 지켜 나가면서 구현해보기로 했다.

처음에는 세 개의 숫자를 문자열로 처리할 생각이다.

이후에 리팩토링을 진행할 때는 Wrapper class로 감싸 3개의 객체로 나누어 보려고 한다.

## 기능 목록
- 게임 기본 입출력 기능
  - 게임 시작 안내 출력
  - 사용자로부터 숫자 입력받기
  - 게임 재시작 및 종료 안내 출력


- 컴퓨터 역할의 임의의 수 3개를 고르는 기능


- 입력받은 문자열의 야구 숫자를 List<Integer>로 변환


- 볼, 스트라이크, 낫싱 관련 기능
  - 입력한 수에 대한 볼, 스트라이크 계산 기능
  - 볼, 스트라이크, 낫싱의 결과를 반환


- 문자열의 야구 숫자 검증
