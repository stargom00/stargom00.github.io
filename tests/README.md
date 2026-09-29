# 테스트 파일
| 파일 | 재현하는 상황 | 복구기에 넣으면 |
|---|---|---|
| nfd-split-names.zip | 맥 NFD 이름 (윈도우에서 풀면 ㄱㅖㅇㅑㄱㅅㅓ) | 풀어서 나온 파일들 → 정상 이름 |
| mac-style-no-utf8-flag.zip | 맥 ZIP, UTF-8 플래그 없음 + 메모.txt 내용 NFD + __MACOSX/.DS_Store | 이름·내용 고침, 찌꺼기 2개 제외 |
| windows-cp949-names.zip | 한글 윈도우 ZIP (CP949 이름). 맥에서 풀면 斑利辑.xlsx | "ZIP 이름" → 견적서.xlsx |
