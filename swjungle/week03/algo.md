# week03
## 컴퓨팅사고로의 전환 - 알고리즘 3주차
---

3주차 주제는 4가지이고 문제 수가 많이 줄었다.
사실상 그래프 탐색이라는 주제가 메인이고 적용하는 방식에 따라 나뉜 주제들이라 실질적으로는 한 가지 주제에 집중하는 주였다고 볼 수 있다.

* 그래프 탐색 기본
    * 1260 - DFS와BFS
    * 2606 - 바이러스

그래프 탐색을 하려면 우선 그래프 형태를 코드로 어떻게 구현해야하는지를 알아야 한다. 각 지점(노드)과 지점들의 연결 부분(간선)을 리스트 또는 딕셔너리 형태로 만들어서 저장하거나 행렬 형태로도 구현할 수 있다.

* BFS
    * 2178 - 미로탐색
    * 7569 - 토마토
    * 3055 - 탈출
    * 2294 - 동전 2

그래프를 탐색하는 한 가지 방법으로 Breadth를 우선하여 같은 레벨에 있는 것들을 먼저 탐색하고 그 다음 레벨로 넘어가서 탐색하는 방식이다. 큐를 활용해서 구현하는데 큐가 스택이 되면 DFS로 변하게 된다. 개념은 쉬운데 같은 레벨의 탐색구간인지 따지는 방법을 구현할 때 다소 애를 먹었다

* DFS
    * 1987 - 알파벳
    * 11725 - 트리의 부모 찾기
    * 2573 - 빙산
    * 2617 - 구슬 찾기

Depth를 우선하는 탐색 방법으로 한 쪽 방향의 최대 탐색 구간까지 다녀온 후에 다음 경로를 탐색하는 방식이다. 재귀로 구현하는 방식과 스택으로 구현하는 방식이 있다. 경우에 따라 각각의 장단점을 따져 DFS와 BFS를 잘 활용할 수 있어야 한다.

* DFS(위상정렬)
    * 2252 - 줄 세우기
    * 2637 - 장난감조립

이것도 개념 자체는 어렵지 않은 것 같은데 막상 글로 설명하려고 하니 쉽지 않다. 간단하게는 연결 고리를 고려한 정렬 이라고 보면 될 것 같은데 자세한 설명은 나중에 추가하도록 하자.

이번 주간은 비슷한 주제들을 집중해서 공부하고 실제 풀어야 하는 문제들도 많지 않아서 week02보다 덜 힘들었고 더 제대로 공부했다는 생각이 들었다. 물론 아직 부족한 게 많지만 하나씩 알아가는 것에 의의를 두도록 해야겠다. 공부하고 문제 푸는 방식에 대해서도 다시 생각해보고 남은 기간도 더욱 의미 있는 시간이 되도록 해야겠다