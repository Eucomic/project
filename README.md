# 에스키모 (Eskimo) 보드게임

![보드판 스크린샷](./assets/board_example.png)  
*Colab에서 그림판 형태로 시각화된 보드 예시*

## 목차
1. [프로젝트 개요](#프로젝트-개요)  
2. [특징(Features)](#특징features)  
3. [필수 조건(Prerequisites)](#필수-조건prerequisites)  
4. [설치 및 실행(Installation & Run)](#설치-및-실행installation--run)  
5. [사용 방법(Usage)](#사용-방법usage)  
   - [텍스트 모드](#텍스트-모드)  
   - [이미지 모드](#이미지-모드)  
6. [디렉터리 구조(Project Structure)](#디렉터리-구조project-structure)  
7. [커스터마이징(Customization)](#커스터마이징customization)  
   - 이미지 교체  
   - 색상/크기 변경  
8. [기여(Contributing)](#기여contributing)  
9. [라이선스(License)](#라이선스license)  
10. [참고 링크(Acknowledgements)](#참고-링크acknowledgements)  

---

## 프로젝트 개요
- 5×5 격자판 위에서 두 명의 플레이어가 번갈아 북극곰을 포위하는 전략 보드게임  
- Colab 환경에서 Python으로 구현, 텍스트·이미지 두 가지 모드 지원  

## 특징(Features)
- 플레이어 말의 슬라이딩 이동  
- 북극곰 1칸 이동 + 4턴 쿨다운  
- 자동 포위 판정  
- 간단한 콘솔 입력 모드 & PIL 기반 이미지 모드  

## 필수 조건(Prerequisites)
- Python 3.7 이상  
- PIL (`Pillow`) 설치:  
  ```bash
  pip install pillow
