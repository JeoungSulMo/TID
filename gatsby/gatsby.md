## 그때그때 알아낸것

### gatsby에서 이미지를 가져오는 방법(경로)

이미지 파일을 가져오기위해 폴더 디렉토리를 타고 들어갔지만 이미지가 나오지않음..

분명히 경로는 맞았지만 이미지가 뜨지 않았고 확인결과 개발 환경에서는 static 폴더안에 있지만 배포이후엔 static 폴더에 내부경로부터 이미지 로드가 가능했음

gatsby에서는 withPrefix라는 함수를 사용해 경로의 접두사를 넣어주는 함수가 있는데 내가 만드는 블로그에선 필요가 없을듯..

경로를 무조건 개발환경에서 가져오는게 아닌 배포 이후 웹팩으로 구성된 경로에 맞춰야 할떄도 있다는걸 잊지말자..
