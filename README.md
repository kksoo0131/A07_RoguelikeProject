## 게임개발 숙련 팀 프로젝트 - 김광수

## Project Introduction

간단한 로그라이크 게임을 목표로 팀원들과

로그라이크 게임에 있는 기능들을 생각하여 만들어 보았습니다.

## Development Period

- 23.09.25 ~ 23.10.04

## Development Environment

Language : C#

Engine : Unity 2022.3.2f1

IDE : Visual Studio 2022

Framework : .NET 6.0

## 내가 구현한 기능

1. 적 몬스터들이 여러 기능 (공격, 이동, 스킬)을 가지고 상황에 맞는 기능을 사용합니다.
   
   - EnemyBehaviour [Wiki](https://github.com/kksoo0131/A07_RoguelikeProject/wiki/EnemyBehaviour)
   - EnemyBehaviourController [Wiki](https://github.com/kksoo0131/A07_RoguelikeProject/wiki/EnemyBehaviourController)
   0- EnemyManager [Wiki](https://github.com/kksoo0131/A07_RoguelikeProject/wiki/EnemyManager)
  
2. 몬스터들이 사용할 각 기능 (공격, 이동, 스킬)들을 구현합니다.

   - IBehaviour [Wiki](https://github.com/kksoo0131/A07_RoguelikeProject/wiki/IBeviour)
   - Bomb
   - CollisionAttack
   - Dead
   - KeepDistance
   - KnockBack
   - LongAttackDistance
   - Move
   - Rush
   - BossAroundAttack
   - BossAroundSafe
   - BossContinuosAttack 

ScriptableObject를 활용해서 데이터를 관리했으면 더 깔끔하게 각 기능들을 몬스터 별로 구현할 수 있었다고 생각합니다.

기능 구현에만 신경을 쓰다가 팀 프로젝트인 전체적인 게임에 신경을 많이 못쓴 부분이 아쉽습니다.

     
