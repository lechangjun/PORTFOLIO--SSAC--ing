# 리눅스 서버 60초안에 상황파악하기

Date: August 25, 2021 → August 26, 2021


`top` 명령어는 위에서 체크해본 다양한 측정치를 쉽게 체크할 수 있다. 시스템 전반적으로 값을 확인하기 쉽다는 장점이 있다. 화면이 지속적으로 바뀌는 점 떄문에 패턴을 찾는것이 어렵다. 일시적으로 멈추는 현상을 잡기 위해서도 화면을 주기적으로 빠르게 멈춰주지 않으면 찾기 힘들다(Ctrl+S는 업데이트를 중지시키고, Ctrl+Q는 다시 시작시킨다), 그리고 화면이 지워져버린다.
