# Spring-Boot-On-GCP-AppEngine

Spring Boot 를 Google Cloud Platform 의 App Engine 에 배포해보는 프로젝트이다

### Instructions

1. [Cloud Console](https://console.cloud.google.com) 에 가서 아래 화면과 같이 프로젝트를 생성한다

2. [App Engine Admin API](https://console.cloud.google.com/marketplace/product/google/appengine.googleapis.com) 를 활성화한다

3. gcloud 를 설치하고 기본 프로젝트로 1에서 생성한 프로젝트를 설정한다

```
brew cask install google-cloud-sdk
gcloud auth application-default login
```

4. 샘플 프로젝트를 배포해본다

```
./gradlew appengineDeployAll
```