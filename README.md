# 🎮 The Unwaking Dream

> **The Backrooms**에서 영감을 받은, '꿈'이라는 요소를 접목시킨 1인칭 심리 공포 방탈출 게임

[![Engine](https://img.shields.io/badge/Engine-Unreal%20Engine%205-313131?logo=unrealengine)](https://www.unrealengine.com/)
[![Genre](https://img.shields.io/badge/Genre-1인칭%20심리%20공포-8B0000)](#)
[![Team](https://img.shields.io/badge/Team-Gamjatang-orange)](#)

<p align="center">
  <a href="https://www.youtube.com/watch?v=BLQDvuzieEo">
    <img src="https://img.youtube.com/vi/BLQDvuzieEo/maxresdefault.jpg" alt="The Unwaking Dream Trailer" width="720">
  </a>
  <br>
  ▶️ <b><a href="https://www.youtube.com/watch?v=BLQDvuzieEo">공식 트레일러 보기</a></b>
</p>

---

## 📖 Summary

한 순간에 미지의 공간 속에 갇힌 플레이어는 괴상한 공간을 돌아다니며 단서를 찾고, 악몽을 꾸게 된 원인을 알아가면서 열쇠를 찾아 탈출하는 것이 목표입니다.

타 공포 게임처럼 기본적인 시스템을 가져가되, 카메라에 **VHS 노이즈 셰이더**와 **볼록렌즈 효과**를 적용하여 플레이어의 시야를 보다 현실적으로 만들고 몰입감을 극대화했습니다.

## 🎲 게임 컨셉

- **개발 환경**: Unreal Engine 5
- **장르**: 1인칭 심리 공포 게임 (First-Person Psychological Horror)
- **컨셉**: *The Backrooms*, *The Classroom* 등 **Liminal Space** 콘셉트를 기반으로, 현실과 비현실이 뒤섞인 몽환적인 공간에서 탈출을 시도하는 플레이어의 심리를 극대화

**VHS 노이즈 셰이더**와 **블룸 렌즈 효과**를 활용해 현실감 있는 몰입도를 제공하며, 다음과 같은 인터랙션 요소를 포함합니다.

| 분류 | 내용 |
|---|---|
| 환경 상호작용 | 문 개폐, 버튼 조작, 배터리 관리, 숨기 시스템 |
| 물리 엔진 활용 | 오브젝트 잡기, 스태미나 시스템, 환경과의 인터랙션 |
| AI 및 애니메이션 | 몬스터 AI 및 애니메이션, 플레이어 행동에 따른 반응 시스템 |
| 사운드/환경 효과 | 플랫폼 소재(Material)에 따라 변화하는 사운드, 빛의 움직임에 따른 환경 변화 |

## 🛠️ 사용 기술 및 라이브러리

- Unreal Engine 5 (Nanite & Lumen)
- Blueprint Scripting
- Animation Blueprint
- Metahuman
- Adobe Photoshop

## 🎲 주요 개발 내용

**① 비주얼 및 환경 디자인**
- Liminal Space 콘셉트를 반영한 초현실적인 공간 디자인
- Nanite & Lumen 기술을 활용한 고품질 조명 및 쉐이더 효과 적용
- VHS 스타일의 포스트 프로세싱(Post-Processing) 효과 적용

**② 게임 메커니즘 및 인터랙션**
- 현실적인 문 개폐 시스템, 버튼 및 오브젝트 상호작용 구현
- 플레이어가 숨을 수 있는 은신 시스템 및 스태미나 시스템 추가
- 플랫폼의 소재(Material)에 따라 사운드가 변화하는 환경 설계

**③ AI 및 몬스터 시스템**
- AI Behavior Tree를 활용한 몬스터 행동 패턴 제작
- 몬스터가 플레이어의 소리를 감지하고 추적하는 AI 시스템 구현
- 애니메이션 및 사운드 디자인을 통한 긴장감 극대화

**④ 팀 협업 및 기여도**
- 레벨 디자인 및 게임 컨셉 아트 기획
- AI 및 인터랙션 시스템 프로그래밍

## 🧩 구현한 주요 블루프린트

`BP_MainMenuWidget` · `BP_NextLevel` · `BP_Notes` · `BP_Menu` · `BP_Dot` · `BP_Doors` · `BP_LockDoorsAndKey` · `BP_FlashLight` · `BP_BatteryPickup` · `BP_Player_RunAndStamina` · `BP_Player_Carry` · `BP_player_Crouch` · `BTT_AI` · `BT_Task_RandomArround` · `BP_AI_ScanAndChase` · `BP_AI_AttackPlayer` · `Monster_Animation` · `BP_EndingCredits` · `VHS` · `3DSound`

## 👥 팀 구성

**Team Gamjatang** — 총 3명

| 담당 | 내용 |
|---|---|
| Design & Animation | 레벨 디자인, 게임 컨셉 아트 기획, 애니메이션 |
| AI & Interaction | AI 및 인터랙션 시스템 프로그래밍 |

## 🗓️ 진행 기간

2024.10.30 ~ 2024.12.13

## 🤔 Learned

- 리미널 스페이스의 공포감을 효과적으로 구현하기 위한 VHS 활용 방법 습득
- AI Behavior Tree, 스태미나 시스템 등 핵심 기능 구현 방법 학습
- 최적화와 AI 행동 로직에서 겪은 도전을 테스트와 조정을 통해 해결

## 🔗 Link

- 📺 [Trailer (YouTube)](https://www.youtube.com/watch?v=BLQDvuzieEo)
