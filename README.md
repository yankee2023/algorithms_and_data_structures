# algorithms_and_data_structures
書籍「プログラミングコンテスト攻略のためのアルゴリズムとデータ構造」の修行

# 初等的配列
- [挿入ソート(Insertion Sort)](ALDS1_1_A_Insertion-Sort/main.cpp)
- [バブルソート(Bubble Sort)](ALDS1_2_A_Bubble-Sort/main.cpp)
- [選択ソート(Selection Sort)](ALDS1_2_B_Selection-Sort/main.cpp)
- [安定なソート(Stable Sort)](ALDS1_2_C_Stable-Sort/main.cpp)
- [シェルソート(Shell Sort)](ALDS1_2_D_Shell-Sort/main.cpp)

# データ構造
- [スタック(Stack)](ALDS1_3_A_Stack/main.cpp)
- [キュー(Queue)](ALDS1_3_B_Queue/main.cpp)
- [双方向連結リスト(Doubly Linked List)](ALDS1_3_C_Doubly-Linked-List/main.cpp)
- [応用: 面積計算](ALDS1_3_D_Areas-on-the-Cross-Section-Diagram/main.cpp)

# STL(Standard Template Library)
- [スタック(Stack)](STL/Stack/main.cpp)
- [キュー(Queue)](STL/Queue//main.cpp)
- [可変長配列(Vector)](STL/Vector/main.cpp)<br>
  要素数がnのvectorに対する特定の位置へのデータ挿入や削除はO(n)の計算量が必要になるので注意。
- [リスト(List)](STL/List/main.cpp)<br>
  ListではVectorのように[]演算子で要素へアクセスできないので注意。<br>
  しかし、ListはVectorと異なり、要素の挿入と削除をO(1)で高速に行うことができる。

# 探索
- [線形探索(Linear Search)](ALDS1_4_A_Linear-Search/main.c)  
  配列の先頭から各要素が目的の値と等しいか順番に調べる。計算量はO(n)。  
- [二分探索(Binary Search)](ALDS1_4_B_Binary-Search/main.c)  
  データが昇順もしくは降順に整列されていることが前提。一回の比較演算を行うごとに探索範囲が半分になっていく性質より、計算量はO(logn)となる。

# メモ
- ラウンドロビンスケジューリング  
- クオンタム  
- 番兵法  
  要素の列の終端にデータを加えることで、ループの終了条件の判定回数を減らすことができる。  
- ループ終了判定  
  - 列の末尾に到達したか  
  - 列のお湯祖が探している値が一致したか  
