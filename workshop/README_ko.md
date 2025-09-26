# GitHub Copilot로 Python 레거시 프로젝트 업그레이드 워크숍

이 워크숍은 GitHub Copilot을 활용하여 Python 2.5 기반의 레거시 프로젝트를 최신 Python 3 버전으로 업그레이드하는 실습을 안내합니다.

## 목표
- 레거시 코드의 주요 문제점 파악 및 업그레이드 전략 수립
- Copilot을 활용한 반복적 코드 개선 및 테스트
- 업그레이드 후 코드의 정상 동작 검증

## 디렉터리 구조
- `legacy/` : 업그레이드 대상이 되는 Python 2.5 레거시 코드
- `upgraded/` : 업그레이드가 완료된 최신 Python 3 코드(직접 작성)
- `guachi/` : 주요 모듈 및 테스트 코드
- `docs/` : Sphinx 기반 문서

## 시작하기
1. `legacy/` 폴더의 코드를 `upgraded/` 폴더로 복사합니다.
2. Copilot의 도움을 받아 Python 3 문법에 맞게 코드를 점진적으로 수정합니다.
3. 각 단계별로 테스트를 실행하여 정상 동작을 확인합니다.

## 주요 실습 내용
- print 문, 예외 처리, 모듈 import 등 Python 2와 3의 주요 차이점 반영
- deprecated된 함수 및 라이브러리 대체
- 테스트 코드 작성 및 자동화
- 문서화(Sphinx 활용)

## 참고 자료
- [Python 공식 문서](https://docs.python.org/3/)
- [GitHub Copilot 공식 안내](https://docs.github.com/en/copilot)

## 기여 방법
Pull Request를 통해 자유롭게 기여해 주세요. 자세한 내용은 상위 디렉터리의 `README_ko.md`를 참고하세요.
