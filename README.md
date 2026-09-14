# 🎮 Unity 클라이언트 개발자
---
## 👋 자기소개
안녕하세요. 저는 Unity와 C#을 기반으로 실시간 3D 콘텐츠와 인터랙티브 시스템을 개발해 온 최민준입니다.<br>
4년간 개인 및 소규모 팀 Unity 프로젝트를 진행하며 사용자 입력, 객체 상태 관리, AI, UI, 물리 상호작용 등 실시간 3D 콘텐츠를 구성하는 주요 기능을 직접 구현해 왔습니다. <br>
프로젝트를 진행하는 과정에서는 단순히 기능을 완성하는 데 그치지 않고, 이후 기능 추가와 수정이 쉽도록 구조를 나누고 유지보수성을 고려해 개발했습니다.<br>
특히 장기간 진행한 3D 프로젝트에서는 입력, 상태, AI, 애니메이션, UI가 서로 연결되는 구조를 직접 구성했으며, 이후에는 Gemini API, MusicGen Server, Unity ML-Agents 등을 활용해 AI 기반 인터랙션과 시뮬레이션 프로젝트로 개발 범위를 확장했습니다.<br>
다양한 프로젝트를 통해 Unity의 여러 기능과 외부 기술을 직접 적용해 왔으며, 새로운 환경에서도 필요한 기술을 빠르게 익히고 실제 기능으로 구현할 수 있는 개발자로 성장하고자 합니다.<br>

---

## 1. TPS 로그라이크 게임
**📅 기간**: 2022.09.20 ~ 2025.03.01<br>
**🧑‍💻 역할**: 기획, 프로그래머<br>
**👥 팀**: 디자이너 1인<br><br>
**🎬 개발 및 구현 영상**:  <br>
[![영상보기](https://img.youtube.com/vi/JgRZtCDci7s/0.jpg)](https://www.youtube.com/watch?v=JgRZtCDci7s)  <br>
**💻 GitHub Repository**: [프로젝트](https://github.com/choiminjun-coder/ShootingStar)<br><br>
**📝 설명**: 3 3년간 진행한 Unity 기반 3D 프로젝트로, 캐릭터 조작부터 전투, AI, 아이템, UI까지 게임을 구성하는 주요 기능을 직접 구현했습니다.<br>
캐릭터 이동과 근·원거리 무기 전환, 애니메이션, FSM 및 NavMesh 기반 적 AI, 상태 변화 시스템을 구현하고 여러 기능이 하나의 플레이 흐름으로 연결되도록 구성했습니다.<br>
기능이 점차 늘어나는 과정에서는 코드 구조를 기능별로 분리하고 모듈화하여, 유지보수와 기능 확장을 고려한 구조로 개선했습니다.<br><br>
**⚙️ 주요 기술**: Unity, C#, FSM, Animator, Coroutine, Raycast, NavMesh  <br>


---
## 2. 실시간 NPC 대화·음악 시스템
**📅 기간**: 2025.11.17 ~ 2025.11.21<br>
**🧑‍💻 역할**: 기획, 프로그래머<br>
**👥 팀**: 없음 <br><br>
**🎬 개발 및 구현 영상**:  <br>
[![영상보기](https://img.youtube.com/vi/-3jB3188iXo/0.jpg)](https://www.youtube.com/watch?v=-3jB3188iXo)  <br>
**💻 GitHub Repository**: [프로젝트](https://github.com/choiminjun-coder/AIChat)<br><br>
**📝 설명**: 사용자의 입력을 기반으로 AI가 NPC 대사를 생성하고, 대화의 분위기에 따라 BGM을 생성·재생하는 Unity 기반 AI 인터랙션 시스템을 구현했습니다.<br>
Gemini API와 MusicGen Server를 Unity와 연동하고 Coroutine 기반 비동기 처리 구조를 구성해 대화 생성부터 음악 재생까지 하나의 흐름으로 연결했습니다.<br>
외부 AI API의 결과를 Unity Runtime의 실제 콘텐츠 변화에 반영하며, AI 기능과 실시간 3D 콘텐츠를 연동하는 시스템을 구축했습니다.<br><br>
**⚙️ 주요 기술**: Unity, C#, Google Gemini API, MusicGen Server  <br>

---

## 3. FPS 미니게임
**📅 기간**: 2024.09.01 ~ 2024.09.30<br>
**🧑‍💻 역할**: 기획, 프로그래머, 멘토<br>
**👥 팀**: 프로그래머 1인<br><br>
**🎬 개발 및 구현 영상**: <br>
[![영상보기](https://img.youtube.com/vi/PqSt6WACUpI/0.jpg)](https://www.youtube.com/watch?v=PqSt6WACUpI)  <br>
**💻 GitHub Repository**: [프로젝트](https://github.com/choiminjun-coder/fps-minigame)<br><br>
**📝 설명**: 무료 에셋만 활용하는 조건에서 기획부터 구현까지 단기간에 완성한 Unity 프로젝트입니다.<br>
Raycast 기반 사격 시스템과 7종의 아이템 효과를 직접 구현하고, 입력 처리, 객체 상호작용, UI 및 Audio가 연동되도록 구성했습니다.<br>
또한 처음 개발을 접하는 팀원에게 시스템 구조와 구현 방식을 설명하고 코드 이해를 지원하며, 기능을 함께 개발하고 문제를 해결하는 협업 경험을 쌓았습니다.<br><br>
**⚙️ 주요 기술**: Unity, C#, Raycast, Coroutine, UI, Audio<br>

---

## 4. 퍼즐 게임
**📅 기간**: 2024.03.01 ~ 2024.10.31<br>
**🧑‍💻 역할**: 프로그래머<br>
**👥 팀**: 프로그래머 2인 <br><br>
**💻 GitHub Repository**: [프로젝트](https://github.com/choiminjun-coder/puzzle-game) <br><br>
**📝 설명**: 3인 팀으로 진행한 Unity 프로젝트로, 색상과 상태 조건에 따라 결과가 달라지는 퍼즐 로직과 클리어 구조를 구현했습니다.<br>
Animator와 Physics를 활용해 객체 상태 변화와 물리 상호작용을 구성하고, 사용자의 입력에 따라 퍼즐 상태가 변화하도록 구현했습니다.<br>
GitHub를 활용해 버전 관리와 코드 피드백을 진행했으며, 팀원들과 기능을 분담하고 개발 과정에서 발생한 문제를 함께 해결했습니다. <br><br>
**⚙️ 주요 기술**: Unity, C#, FSM, Animator, Physics<br>

---

## 5. Unity ML-Agents 강화학습
**📅 기간**: 2026.01.02 ~ 2026.01.28<br>
**🧑‍💻 역할**: 강화학습 시스템 설계 및 개발, 기술 교육 자료 제작 <br>
**👥 팀**: 프로그래머 1인 <br><br>
**🎬 개발 및 구현 영상**: <br>
[![영상보기](https://img.youtube.com/vi/eOJz3_gD0i4/0.jpg)](https://www.youtube.com/watch?v=eOJz3_gD0i4)  <br>
**💻 GitHub Repository**: [프로젝트](https://github.com/choiminjun-coder/Unity-MLAgents-Autonomous-Vehicles) <br><br>
**📝 설명**: Unity ML-Agents 기반으로 드론과 자동차 에이전트를 구현하고, Ray 기반 관찰값과 연속형 Action을 설계해 목표 지점에 도달하도록 학습시키는 강화학습 프로젝트입니다.<br>
학습 환경에서 관찰–행동–보상 흐름을 직접 구성하고, 목표 탐지·접근·충돌·시간 제한 등 상황별 Reward를 설계해 에이전트가 안정적으로 학습할 수 있도록 환경을 구성했습니다.<br>
Unity를 AI 에이전트의 학습과 동작을 검증하는 3D 시뮬레이션 환경으로 활용했습니다.<br><br>
**⚙️ 주요 기술**: Unity, C#, Unity ML-Agents <br>

---

## 6. MIO: Akihabara AI Talk
**📅 기간**: 2026.08.03 ~ 2026.08.05<br>
**🧑‍💻 역할**: 기획, 프로그래머<br>
**👥 팀**: 개인 프로젝트 <br><br>
**🎬 개발 및 구현 영상**:  <br>
[![영상보기](https://img.youtube.com/vi/uR3xFIhhQsY/0.jpg)](https://www.youtube.com/watch?v=uR3xFIhhQsY)  <br>
**💻 GitHub Repository**:  <br>
- [Source Code](https://github.com/Choi-Min-Jun-1/MIO_Akihabara_AI_Talk_Source)<br>
- [Android APK](https://github.com/Choi-Min-Jun-1/MIO_Akihabara_AI_Talk_Apk)<br>

**📝 설명**: Unity 기반 Android 3D 환경에서 사용자가 자유롭게 입력한 문장에 AI NPC가 실시간으로 응답하고 음성으로 출력하는 인터랙션 시스템을 구현했습니다.<br>
Gemini API를 활용해 NPC의 캐릭터 설정에 맞는 대사를 생성하고, Google Cloud Text-to-Speech를 연동해 생성된 대사를 실시간 음성으로 재생하도록 구성했습니다.<br>
Google Apps Script를 AI Gateway로 구성해 Unity와 외부 AI API의 요청·응답 흐름을 분리했으며, Android APK 환경에서 이동, NPC 상호작용, 대화 입력, AI 응답 및 음성 재생까지 전체 흐름을 직접 구현하고 검증했습니다.<br><br>
**⚙️ 주요 기술**: Unity, C#, Gemini API, Google Cloud Text-to-Speech, Google Apps Script<br>

---
