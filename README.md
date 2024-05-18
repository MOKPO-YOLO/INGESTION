# YOLO 팀 프로젝트 Repository

<br>

YOLO 팀은 X-Ray 를 활용한 이미지를 분석하는 모델과 여러 모델을 서비스할 수 있는 플랫폼을 제작합니다.

<br><br>


# 구성원

<br>

- 손채영 팀장
- 오진희
- 오종원
- 임찬혁

<br><br>

# 협업 규칙

<br>

반드시 협업 규칙을 준수합니다.

1. 데잍리 회의를 진행한 후 나온 요건들을 팀장님이 이슈합니다.
2. 해당 이슈에 대한 역할 분담을 반드시 진행합니다.
3. 티켓팅 된 이슈 번호에 맞춰 branch 작성 합니다.
4. PR 은 반드시 검수 후 통과합니다.
5. Jira 에 Task 별 일정을 준수 합니다.

### branch 설명


|  branch 명 | 설명 | 비고 |
| --- | --- | --- |
| main | 출시 branch, 해당 branch 로 버전이 관리되며 실제로 서비스 하는 App 소스가 담겨 있습니다. | |
| develop | 통합 테스트 branch, 각 이슈(요소/기능)별로 만들어진 feature 브랜치 들이 merge 되어 통합 테스트하는 branch 입니다. | |
| feature | 각 이슈(요소/기능)들을 독립된 공간에서 개발하기 위해 만들어지는 브랜치 입니다. 항상 develop 에서 branch 가 시작됩니다. | ex. 이슈 번호 #1 > feature/#1 |
| release | develop branch 에서 통합 테스트를 마친 후 마지막으로 품질 검사 및 배포하기 가장 전 단계 branch 입니다. 수정 후 배포는 main, develop 입니다. | ex. 이슈 번호 #1 > release/#1 |
| hotfix | 긴급하게 수정이 필요할 경우 main 에서 바로 branch 하여 작성 후 merge 할 수 있는 branch 입니다. | ex. 이슈 번호 #1 > hotfix/#1 |


<br><br>
