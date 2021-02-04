# greedy
Studying greedy

1. 최적해를 구하기 위해 사용되는 근사적인 방식
   -> 결정해야되는 '순간(local)'에 최적이라고 생각되는 것을 선택해나가는 방식
   1-1. 전체(global)로 봤을 때 항상 최적인 것은 아니다.
        그러므로 최적해가 맞는지 증명해야 한다.
2. Greedy Choice Property & Optimal Substructure 만
   ㄱ. Greedy Choice Property
       : sub-problem의 해답이 다음 sub-problem에 영향을 주지 않는다.
   ㄴ. Optimal Substructure
       : 문제 전체(global)의 최적해가 sub-problem의 최적해도 된다.
3. 순간순간 최적을 골라감으로 속도가 빠르다.
   -> 실용적으로 사용 가능
4. 알고리즘의 이용
   ㄱ. 거스름돈 문제 / 분할 가능한 배낭 채우기 문제
       - 큰 값부터 값을 대입하여 결과를 추출
   ㄴ. MST(Minimum Spanning Tree)
       - 추후 추가
   ㄷ. Dijkstra Algorithm(다익스트라 알고리즘)
       - 시작 정점에서 도착 정점까지의 최단거리를 구하는 알고리즘
       - 현재 위치한 정점에서 연결된 모든 정점까지의 거리(가중치)를 구하고
         방문하지 않은 정점에서 동일한 과정을 반복하여
         도착 정점까지의 최단 거리를 구한다.
   
