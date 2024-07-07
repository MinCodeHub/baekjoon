# Binary Search (이분탐색)

[메인으로 돌아가기](https://github.com/tony9402/baekjoon)

풀어보면 좋을 문제는 추천 문제에 체크(:heavy_check_mark:) 해놨습니다.

추천 문제 아닌 나머지는 나머지를 난이도 섞었습니다.

<br>

***❗️❗️꼭 문제를 순서대로 안풀어도 됩니다.❗️❗️***

[백준 문제집](https://www.acmicpc.net/workbook/view/7277)


|순번|추천 문제|문제 번호|문제 이름|난이도|풀이 링크|
|:--:|:--:|:--:|:--:|:--:|:--:|
|000|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/1789" target="_blank">1789</a>|<a href="https://www.acmicpc.net/problem/1789" target="_blank">수들의 합</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/6.svg"/>|<a href="./../solution/binary_search/1789" target="_blank">바로 가기</a>|
|001|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/10815" target="_blank">10815</a>|<a href="https://www.acmicpc.net/problem/10815" target="_blank">숫자 카드</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/6.svg"/>|<a href="./../solution/binary_search/10815" target="_blank">바로 가기</a>|
|002|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2417" target="_blank">2417</a>|<a href="https://www.acmicpc.net/problem/2417" target="_blank">정수 제곱근</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/>|<a href="./../solution/binary_search/2417" target="_blank">바로 가기</a>|
|003|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/19637" target="_blank">19637</a>|<a href="https://www.acmicpc.net/problem/19637" target="_blank">IF문 좀 대신 써줘</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>|<a href="./../solution/binary_search/19637" target="_blank">바로 가기</a>|
|004|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/11663" target="_blank">11663</a>|<a href="https://www.acmicpc.net/problem/11663" target="_blank">선분 위의 점</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|005|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/1654" target="_blank">1654</a>|<a href="https://www.acmicpc.net/problem/1654" target="_blank">랜선 자르기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>|<a href="./../solution/binary_search/1654" target="_blank">바로 가기</a>|
|006|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2805" target="_blank">2805</a>|<a href="https://www.acmicpc.net/problem/2805" target="_blank">나무 자르기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>|<a href="./../solution/binary_search/2805" target="_blank">바로 가기</a>|
|007|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2512" target="_blank">2512</a>|<a href="https://www.acmicpc.net/problem/2512" target="_blank">예산</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>|<a href="./../solution/binary_search/2512" target="_blank">바로 가기</a>|
|008|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/22871" target="_blank">22871</a>|<a href="https://www.acmicpc.net/problem/22871" target="_blank">징검다리 건너기 (large)</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|009|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/3079" target="_blank">3079</a>|<a href="https://www.acmicpc.net/problem/3079" target="_blank">입국심사</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>|<a href="./../solution/binary_search/3079" target="_blank">바로 가기</a>|
|010|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2470" target="_blank">2470</a>|<a href="https://www.acmicpc.net/problem/2470" target="_blank">두 용액</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>|<a href="./../solution/binary_search/2470" target="_blank">바로 가기</a>|
|011|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/20444" target="_blank">20444</a>|<a href="https://www.acmicpc.net/problem/20444" target="_blank">색종이와 가위</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>|<a href="./../solution/binary_search/20444" target="_blank">바로 가기</a>|
|012|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2412" target="_blank">2412</a>|<a href="https://www.acmicpc.net/problem/2412" target="_blank">암벽 등반</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|013|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/1477" target="_blank">1477</a>|<a href="https://www.acmicpc.net/problem/1477" target="_blank">휴게소 세우기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>|<a href="./../solution/binary_search/1477" target="_blank">바로 가기</a>|
|014|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2110" target="_blank">2110</a>|<a href="https://www.acmicpc.net/problem/2110" target="_blank">공유기 설치</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>|<a href="./../solution/binary_search/2110" target="_blank">바로 가기</a>|
|015|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/13397" target="_blank">13397</a>|<a href="https://www.acmicpc.net/problem/13397" target="_blank">구간 나누기 2</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|016|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/1939" target="_blank">1939</a>|<a href="https://www.acmicpc.net/problem/1939" target="_blank">중량제한</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>||
|017|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/2473" target="_blank">2473</a>|<a href="https://www.acmicpc.net/problem/2473" target="_blank">세 용액</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>||
|018|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/7453" target="_blank">7453</a>|<a href="https://www.acmicpc.net/problem/7453" target="_blank">합이 0인 네 정수</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||
|019|:heavy_check_mark:|<a href="https://www.acmicpc.net/problem/1300" target="_blank">1300</a>|<a href="https://www.acmicpc.net/problem/1300" target="_blank">K번째 수</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/15.svg"/>||
|020||<a href="https://www.acmicpc.net/problem/1920" target="_blank">1920</a>|<a href="https://www.acmicpc.net/problem/1920" target="_blank">수 찾기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/>|<a href="./../solution/binary_search/1920" target="_blank">바로 가기</a>|
|021||<a href="https://www.acmicpc.net/problem/2776" target="_blank">2776</a>|<a href="https://www.acmicpc.net/problem/2776" target="_blank">암기왕</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/>|<a href="./../solution/binary_search/2776" target="_blank">바로 가기</a>|
|022||<a href="https://www.acmicpc.net/problem/20551" target="_blank">20551</a>|<a href="https://www.acmicpc.net/problem/20551" target="_blank">Sort 마스터 배지훈의 후계자</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/>||
|023||<a href="https://www.acmicpc.net/problem/10816" target="_blank">10816</a>|<a href="https://www.acmicpc.net/problem/10816" target="_blank">숫자 카드 2</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/>|<a href="./../solution/binary_search/10816" target="_blank">바로 가기</a>|
|024||<a href="https://www.acmicpc.net/problem/17266" target="_blank">17266</a>|<a href="https://www.acmicpc.net/problem/17266" target="_blank">어두운 굴다리</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/>||
|025||<a href="https://www.acmicpc.net/problem/16960" target="_blank">16960</a>|<a href="https://www.acmicpc.net/problem/16960" target="_blank">스위치와 램프</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/7.svg"/>||
|026||<a href="https://www.acmicpc.net/problem/1166" target="_blank">1166</a>|<a href="https://www.acmicpc.net/problem/1166" target="_blank">선물</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|027||<a href="https://www.acmicpc.net/problem/1072" target="_blank">1072</a>|<a href="https://www.acmicpc.net/problem/1072" target="_blank">게임</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|028||<a href="https://www.acmicpc.net/problem/11561" target="_blank">11561</a>|<a href="https://www.acmicpc.net/problem/11561" target="_blank">징검다리</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|029||<a href="https://www.acmicpc.net/problem/17451" target="_blank">17451</a>|<a href="https://www.acmicpc.net/problem/17451" target="_blank">평행 우주</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|030||<a href="https://www.acmicpc.net/problem/17124" target="_blank">17124</a>|<a href="https://www.acmicpc.net/problem/17124" target="_blank">두 개의 배열</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|031||<a href="https://www.acmicpc.net/problem/17393" target="_blank">17393</a>|<a href="https://www.acmicpc.net/problem/17393" target="_blank">다이나믹 롤러</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|032||<a href="https://www.acmicpc.net/problem/2121" target="_blank">2121</a>|<a href="https://www.acmicpc.net/problem/2121" target="_blank">넷이 놀기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|033||<a href="https://www.acmicpc.net/problem/7795" target="_blank">7795</a>|<a href="https://www.acmicpc.net/problem/7795" target="_blank">먹을 것인가 먹힐 것인가</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/8.svg"/>||
|034||<a href="https://www.acmicpc.net/problem/14627" target="_blank">14627</a>|<a href="https://www.acmicpc.net/problem/14627" target="_blank">파닭파닭</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>||
|035||<a href="https://www.acmicpc.net/problem/18113" target="_blank">18113</a>|<a href="https://www.acmicpc.net/problem/18113" target="_blank">그르다 김가놈</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>||
|036||<a href="https://www.acmicpc.net/problem/15810" target="_blank">15810</a>|<a href="https://www.acmicpc.net/problem/15810" target="_blank">풍선 공장</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>||
|037||<a href="https://www.acmicpc.net/problem/6236" target="_blank">6236</a>|<a href="https://www.acmicpc.net/problem/6236" target="_blank">용돈 관리</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>|<a href="./../solution/binary_search/6236" target="_blank">바로 가기</a>|
|038||<a href="https://www.acmicpc.net/problem/13702" target="_blank">13702</a>|<a href="https://www.acmicpc.net/problem/13702" target="_blank">이상한 술집</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>||
|039||<a href="https://www.acmicpc.net/problem/16401" target="_blank">16401</a>|<a href="https://www.acmicpc.net/problem/16401" target="_blank">과자 나눠주기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/9.svg"/>||
|040||<a href="https://www.acmicpc.net/problem/14575" target="_blank">14575</a>|<a href="https://www.acmicpc.net/problem/14575" target="_blank">뒤풀이</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|041||<a href="https://www.acmicpc.net/problem/17503" target="_blank">17503</a>|<a href="https://www.acmicpc.net/problem/17503" target="_blank">맥주 축제</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|042||<a href="https://www.acmicpc.net/problem/2343" target="_blank">2343</a>|<a href="https://www.acmicpc.net/problem/2343" target="_blank">기타 레슨</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|043||<a href="https://www.acmicpc.net/problem/16564" target="_blank">16564</a>|<a href="https://www.acmicpc.net/problem/16564" target="_blank">히오스 프로게이머</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|044||<a href="https://www.acmicpc.net/problem/2792" target="_blank">2792</a>|<a href="https://www.acmicpc.net/problem/2792" target="_blank">보석 상자</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|045||<a href="https://www.acmicpc.net/problem/11687" target="_blank">11687</a>|<a href="https://www.acmicpc.net/problem/11687" target="_blank">팩토리얼 0의 개수</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/10.svg"/>||
|046||<a href="https://www.acmicpc.net/problem/18114" target="_blank">18114</a>|<a href="https://www.acmicpc.net/problem/18114" target="_blank">블랙 프라이데이</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|047||<a href="https://www.acmicpc.net/problem/17179" target="_blank">17179</a>|<a href="https://www.acmicpc.net/problem/17179" target="_blank">케이크 자르기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|048||<a href="https://www.acmicpc.net/problem/2467" target="_blank">2467</a>|<a href="https://www.acmicpc.net/problem/2467" target="_blank">용액</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|049||<a href="https://www.acmicpc.net/problem/2866" target="_blank">2866</a>|<a href="https://www.acmicpc.net/problem/2866" target="_blank">문자열 잘라내기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|050||<a href="https://www.acmicpc.net/problem/9024" target="_blank">9024</a>|<a href="https://www.acmicpc.net/problem/9024" target="_blank">두 수의 합</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>|<a href="./../solution/binary_search/9024" target="_blank">바로 가기</a>|
|051||<a href="https://www.acmicpc.net/problem/20495" target="_blank">20495</a>|<a href="https://www.acmicpc.net/problem/20495" target="_blank">수열과 헌팅</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|052||<a href="https://www.acmicpc.net/problem/3020" target="_blank">3020</a>|<a href="https://www.acmicpc.net/problem/3020" target="_blank">개똥벌레</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/11.svg"/>||
|053||<a href="https://www.acmicpc.net/problem/16434" target="_blank">16434</a>|<a href="https://www.acmicpc.net/problem/16434" target="_blank">드래곤 앤 던전</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|054||<a href="https://www.acmicpc.net/problem/8983" target="_blank">8983</a>|<a href="https://www.acmicpc.net/problem/8983" target="_blank">사냥꾼</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|055||<a href="https://www.acmicpc.net/problem/22945" target="_blank">22945</a>|<a href="https://www.acmicpc.net/problem/22945" target="_blank">팀 빌딩</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|056||<a href="https://www.acmicpc.net/problem/2022" target="_blank">2022</a>|<a href="https://www.acmicpc.net/problem/2022" target="_blank">사다리</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/12.svg"/>||
|057||<a href="https://www.acmicpc.net/problem/12757" target="_blank">12757</a>|<a href="https://www.acmicpc.net/problem/12757" target="_blank">전설의 JBNU</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>||
|058||<a href="https://www.acmicpc.net/problem/2143" target="_blank">2143</a>|<a href="https://www.acmicpc.net/problem/2143" target="_blank">두 배열의 합</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>|<a href="./../solution/binary_search/2143" target="_blank">바로 가기</a>|
|059||<a href="https://www.acmicpc.net/problem/17951" target="_blank">17951</a>|<a href="https://www.acmicpc.net/problem/17951" target="_blank">흩날리는 시험지 속에서 내 평점이 느껴진거야</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/13.svg"/>||
|060||<a href="https://www.acmicpc.net/problem/9007" target="_blank">9007</a>|<a href="https://www.acmicpc.net/problem/9007" target="_blank">카누 선수</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||
|061||<a href="https://www.acmicpc.net/problem/2613" target="_blank">2613</a>|<a href="https://www.acmicpc.net/problem/2613" target="_blank">숫자구슬</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||
|062||<a href="https://www.acmicpc.net/problem/15823" target="_blank">15823</a>|<a href="https://www.acmicpc.net/problem/15823" target="_blank">카드 팩 구매하기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||
|063||<a href="https://www.acmicpc.net/problem/15732" target="_blank">15732</a>|<a href="https://www.acmicpc.net/problem/15732" target="_blank">도토리 숨기기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||
|064||<a href="https://www.acmicpc.net/problem/6209" target="_blank">6209</a>|<a href="https://www.acmicpc.net/problem/6209" target="_blank">제자리 멀리뛰기</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/14.svg"/>||
|065||<a href="https://www.acmicpc.net/problem/1561" target="_blank">1561</a>|<a href="https://www.acmicpc.net/problem/1561" target="_blank">놀이 공원</a>|<img height="25px" width="25px" src="https://static.solved.ac/tier_small/15.svg"/>||