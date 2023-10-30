ex04: 애플리케이션 bundling(번들링)

1. webpack은 작게 분리된 애플리케이션 모듈(js, css, scss/sass, images, font)들을 '의존성 분석'을 하여 하나의 js로 묶는 도구.
2. 최종 결과물인 하나의 js 파일을 번들(bundle)이라 하고 묶는 작업을 번들링(bundling)이라 한다.
3. 번들링은 단순히 모듈들을 하나의 파일로 묶는 작업을 의미하지 않는다.
4. 빌드 작업(js)
    - linting(Eslint, 문법 체크) 작업
    - document(JSDocs) 작업
    - test(Mocha, jest) 작업
    - 난독/압축(uglify) 작업
    - 번들링
5. js 모듈 뿐만 아니라 다양한 에셋(images, css, sass/scss, font)들도 모듈로 취급한다.