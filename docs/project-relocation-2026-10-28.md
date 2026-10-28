# 프로젝트 이름과 작업 위치

2026-10-28에 기준 작업 위치를 `G:\dev\workbench-terrain-noise`로 정리했다. 이전 위치는 `C:\dev\repo-catalog-to-remove\terrain-noise-workbench-2026`다.

원격 저장소는 [five2nine/workbench-terrain-noise](https://github.com/five2nine/workbench-terrain-noise)이며 기존 저장소의 고유 ID `1249523880`와 Git 이력 및 공개 범위를 유지했다. 제품 내부 패키지와 실행 파일의 기존 이름은 유지한다.

이동 직후 Git 내부를 제외한 파일 3,761개의 목록과 크기를 대조했고, 재생성 가능한 의존성 캐시를 제외한 79개의 SHA-256이 일치했다. 이후 현재 경로를 사용하는 문서와 설정을 갱신했다. 원자료와 모델, 기존 실행 파일 및 사용자 파일은 보존했다.

SQLite DB 0개는 이동 전에 일관된 백업을 만들고 `quick_check`와 테이블별 행 수를 기록했다. 기존 로컬 변경은 이름 변경 커밋에 포함하지 않았다. 재생성 가능한 환경과 빌드 경로의 복구 및 실제 수행한 점검은 로컬 작업 기록에 구분해 남겼다. 앱의 실제 화면 조작과 외부 서비스 동작은 이번 정리에서 시험하지 않았다.
