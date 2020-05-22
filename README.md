# react-practice repo

이 블로그는 `리액트를 다루는 기술`의 실습 코드들을 저장하며 연습하는 곳입니다.

## 13장 - 리액트 라우터로 SPA 개발하기 정리

이 장에서는 리액트 라우터를 사용하여 주소 경로에 따라 다양한 페이지를 보여주는 방법을 알아보았습니다.  
큰 규모의 프로젝트를 진행하다 보면 한 가지 문제가 발생합니다.

바로 웹 브라우저에서 사용할 컴포넌트, 상태관리 로직, 그 외 여러 기능을 구현하는 함수들이 점점 쌓이면서 최종 결과물인  
자바스크립트 파일의 크기가 매우 커진다는 점입니다.

예를 들어 방금 만든 프로젝트는 사용자가 /about 페이지에 들어왔을 때 지금 당장 필요하지 않은 Profile 컴포넌트까지 불러옵니다.  
라우트에 따라 필요한 컴포넌트만 불러오고, 다른 컴포넌트는 다른 페이지를 방문하는 등의 필요한 시점에 불러오면 더 효율적이지 않을까요?  
이를 해결해주는 기술이 바로 코드 스플리팅입니다.