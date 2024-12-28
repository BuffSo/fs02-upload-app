## S3 파일 업로드 예제
* 이 프로젝트는 Express 서버와 AWS S3를 이용해 파일 업로드를 구현하는 간단한 예제입니다.

### 기능

* HTML을 통해 파일을 선택하고 업로드
* Express 서버에서 AWS S3의 signed URL을 발급받아 파일 업로드
* CORS 설정으로 로컬 환경에서의 API 호출 허용

### 요구사항

* Node.js 14 이상
* AWS S3 버킷 및 IAM 사용자 (업로드 권한 필요)

### 환경 변수 설정
```
AWS_REGION=your_aws_region
AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key
AWS_BUCKET_NAME=your_bucket_name
```