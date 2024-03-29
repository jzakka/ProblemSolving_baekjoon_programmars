# [Platinum II] Bridge - 4381 

[문제 링크](https://www.acmicpc.net/problem/4381) 

### 성능 요약

메모리: 12216 KB, 시간: 88 ms

### 분류

해 구성하기, 그리디 알고리즘

### 문제 설명

<p><i>n</i> people wish to cross a bridge at night. A group of at most two people may cross at any time, and each group must have a flashlight. Only one flashlight is available among the <i>n</i> people, so some sort of shuttle arrangement must be arranged in order to return the flashlight so that more people may cross.</p>

<p>Each person has a different crossing speed; the speed of a group is determined by the speed of the slower member. Your job is to determine a strategy that gets all <i>n</i> people across the bridge in the minimum time.</p>

### 입력 

 <p>The first line of input contains <i>n</i>, followed by <i>n</i> lines giving the crossing times for each of the people. There are not more than 1000 people and nobody takes more than 100 seconds to cross the bridge.</p>

### 출력 

 <p>The first line of output must contain the total number of seconds required for all <i>n</i> people to cross the bridge. The following lines give a strategy for achieving this time. Each line contains either one or two integers, indicating which person or people form the next group to cross. (Each person is indicated by the crossing time specified in the input. Although many people may have the same crossing time the ambiguity is of no consequence.) Note that the crossings alternate directions, as it is necessary to return the flashlight so that more may cross. If more than one strategy yields the minimal time, any one will do.</p>

