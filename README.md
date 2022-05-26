# coding-test6
K번째수

  * 매개변수
    1. 배열 array
    2. [i, j, k]를 원소로 가진 2차원 배열 commands

## 구현과정 - 틀림
  1. 배열 array의 i번째 숫자부터 j번째 숫자까지 자르고 정렬했을 때, k번째에 있는 수
      - 배열 array의 i번째 숫자부터 j번째 숫자까지 자름
        > 배열복사 System.arraycopy(원본, 원본시작점, 복사본, 복사본시작점, 복사갯수)
      - 정렬
        > Arrays.sort(배열명)

## 보완할점
  1. 배열복사 > Arrays.copyOfRange(원본, 원본시작인덱스, 원본끝인덱스)  :  시작부터 끝인덱스 직전까지 복사
  2. 반환할 배열 선언 > int[] answer = new int[commands.length];
