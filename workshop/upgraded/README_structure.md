# upgraded 폴더 구조 설명

`upgraded` 폴더는 레거시(`legacy`) 폴더의 전체 파일과 디렉터리 구조를 복사한 디렉터리입니다. 이 폴더는 레거시 코드를 최신 Python 환경에 맞게 업그레이드하거나 실험하는 공간으로 활용됩니다.

## 주요 하위 폴더 및 파일

- `MANIFEST.in`, `README.rst`, `distribute-0.6.10.tar.gz`, `distribute_setup.py`, `setup.py`: 프로젝트 메타 정보, 설치 스크립트, 배포 관련 파일
- `docs/`: 프로젝트 문서 관련 폴더
  - `build/`: 빌드된 문서(HTML, doctree 등)
  - `source/`: Sphinx 등으로 작성된 문서 원본(rst, conf.py 등)
- `guachi/`: 주요 Python 패키지 소스 코드
  - `__init__.py`, `config.py`, `database.py`: 핵심 모듈
  - `tests/`: 단위 테스트 및 통합 테스트 코드
- `guachi.egg-info/`: 패키징 정보(egg 메타데이터)

## 활용 목적
- 레거시 코드를 최신 Python 버전으로 변환 및 실험
- 테스트 및 문서화, 패키징 실습
- 업그레이드 전/후 비교 및 자동화 실습

> 이 폴더 내의 파일을 자유롭게 수정하며 업그레이드 실습을 진행할 수 있습니다.
