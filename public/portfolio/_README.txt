Portfolio Asset 수집 폴더
=========================

이 폴더는 포트폴리오 사이트용 이미지·영상 에셋을 프로젝트별로 모으는 곳입니다.

폴더 명명 규칙:
  {NN}_{YYYYMM}_{Title}

  - NN: 역시간순 순번 (01 = 최신, 36 = 가장 오래된 것)
  - YYYYMM: 시기 (예: 202602)
  - Title: 영문 프로젝트명

각 프로젝트 폴더 하위:
  thumbnails/   → 리스트 뷰 썸네일용 이미지 (1~3장 권장)
  detail/       → 디테일 뷰 이미지 (hero / wide / pair / medium 등)
  _info.txt     → 프로젝트 메타데이터 (Title, Client, Agency, Tags, 원본 경로)

디테일 뷰 이미지 슬롯 (index.html 참고):
  hero     → 16:10 aspect ratio
  wide     → 16:9
  pair     → 4:5 x 2 (좌/우)
  medium   → 3:2

파일명 권장:
  01_hero.jpg, 02_wide.jpg, 03_pair-left.jpg, 04_pair-right.jpg, 05_medium.jpg, 06_wide.jpg

Index 파일:
  _index.csv — 36개 프로젝트 전체 목록 (엑셀로 열 수 있음)
