# scss-extension


- 확장 프로그램 테스트 및 실행
프로젝트가 완성되면 다음 명령어로 확장 프로그램을 컴파일하고 실행할 수 있습니다:

```
npm run compile
```

VS Code에서 F5를 눌러 확장 프로그램을 실행하고, 사이드바에서 SCSS 변수들을 확인



- 패키징 및 배포
확장 프로그램이 완성되면 vsce를 사용하여 패키징하고 VS Code Marketplace에 배포할 수 있습니다:

```
npm install -g vsce
vsce package
```