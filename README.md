sesac-test

Main branch : 최종배포
Develop branch : 개발 진행되는 중인 브랜치
Feature branch : 특정 기능 개발 하는 별도의 브랜치
Release branch : 배포 전 테스트 및 마무리 작업을 위한 브랜치
Hotfix branch : 긴급한 오류나 버그 수정을 위한 브랜치

##User 정보에 대한 API를 구축할 때는 develop 브랜치에서 feature 브랜치를 파생해서 해당 API를 구축하고 구축이 완료되면 develop 브랜치로 merge 하고, develop 브랜치에서 모든 작업이 완료되면 develop 브랜치의 내용을 main 으로 merge 해서 최종 완성(배포)본
##main 브랜치에서 개발을 위한 develop 브랜치를 파생시키고 feature 브랜치에서 기능별 개발을 진행 후 develop 으로 merge 하는 흐름
