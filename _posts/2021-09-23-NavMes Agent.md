---
layout: single
title:  "Nav Mesh Agent"
---
길찾기 알고리즘 이용 
ai 기능 유니티만

Speed 속도
Angular Speed 얼마나 빠르게 돌건지
Acceleration 가속력
Stopping Distance 목적지와의 거리,멈출거리 (어택범위와 같게해야함
Auto Braking 알아서 멈추다

성능 많이 잡아먹어서 잘안씀

NavMeshAgent는 using UnityEngine.AI; 가 있어야 사용가능하다

ex) NavMeshAgent  _agent = null;

start
{
    _agent = GetComponent<NavMeshAgent>();
}


SetDestination (목적지 까지이동)

Window -> AI -> Navigation

Agent Radius (기울기)
Agent Height (장애물 등을 통과하기 위한 에이전트의 높이)
Step Height (올라갈 수 있는 높이를 의미)
