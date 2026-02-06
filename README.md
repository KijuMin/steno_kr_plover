# steno_kr_plover

_______________________________________________________________________


1번 -----1번의 완료------

Plover 속기 프로그램 다운로드 하는법(윈도우용)

주소로 이동 --> https://github.com/opensteno/plover/releases 

아래로 내리면 v4.0.3버전의 ‘Assets’ 클릭 

‘Windows: installer’ 다운로드 

실행한 다음 ’추가정보’ 누르고 ’실행’ 누르기

‘Install for anyone using this computer’ 로 선택하고 NEXT 누르기 

계속 NEXT하기 마지막에 ‘Install’ 하기

 


______________________________________________________________________

2번  **중요**



한국 속기 플러그인 다운로드와 Plover 프로그램에 불러오는법 


주소로 이동 후 다운로드 --> https://github.com/nsmarkop/plover_korean 

다운로드한 압축된 파일을 압축 풀기 

압축 푼 파일 안에 있는 ‘plover_korean-master'의 파일 이름을 ‘plover_korean’으로 바꾸기 

예시) 제대로 이름을 수정했으면 이렇게 경로가 되어있음
---> C:\Users\사용자이름\Downloads\plover_korean-master\plover_korean

검색기에 CMD를 관리자 권한으로 실행하고 아래 문장을 쓰고 엔터(순서대로 한 줄씩) 


-----     cd C:\Program Files\Open Steno Project\Plover 4.0.3 

-----     Plover_console.exe -s plover_plugins install “C:\Users\사용자이름\Downloads\plover_korean-master\plover_korean” 



“Successfully installed plover-korean-0.0.3” <-- 문장이 뜨면 성공 

Plover 프로그램을 실행하고 프로그램 왼쪽 상단에 File --> configure --> system --> korean modern C 바꾸기(원래는 English Stenotype로 설정되어있음) 



______________________________________________________________________________

3번


Plover 프로그램에 약어파일들 불러오는법/(약어 추가하는법) 

1. 하단 중앙에 + 버튼 클릭 후‘load dictionaries’ 클릭 후 받은 ’약어_JSON파일들’ 다 불러오기(옵션) 
 
2. 약어를 추가하는법(옵션)
원하는 파일을 클릭 후 ‘By strokes‘에는 원하는 조합 
‘By translation‘에는 원하는 출력값 적기(단어나, 문장) 
 
3. plover 프로그램을 키면 바로 오른쪽에 있는 Output에 있는 'Enabled'를 클릭하고 키보드에 있는 TG키(맨 아래 맨 오른쪽 키) 
누르면 속기 자판으로 바뀌고 속기가 가능해집니다 
 
 
____________________________________________________________________________
 

 

 

 

 
