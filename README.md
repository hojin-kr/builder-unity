# builder-unity-ci
github Action을 활용한 Unity Builder-ci   
https://github.com/game-ci/unity-builder

## 특징
- just-build : 빌드를 수행 후 apk, ios project 파일을 artifact로 저장합니다.
- releaseToGooglePlay : 빌드 수행 후 google Play의 테스트 트랙으로 배포합니다.
- remove-old-artifacts : github 비용 관리를 위해 매일 정해진 시간에 저장된 artifact를 제거하여 저장소를 비웁니다.

### 버전
workflow 실행시 명시적으로 지정합니다. 
![image](https://user-images.githubusercontent.com/22079767/141799344-bbb3548b-89e9-42aa-90ec-a63608e7d1b2.png)
