##setting.py 에 static 폴더 설정

장고 공식 문서 [링크](https://docs.djangoproject.com/ko/4.0/howto/static-files/)

STATIC_URL 의미
- {% static url~~~~ %} 이라고 적을때 prefix에 해당하는 부분이 할당된다.

STATICFILES_DIR
- 개발자가 할당해줘야 하는 부분이고, 오늘 13시간정도를 날리게 한 장본인. STATIC S FILES_DIR 이 아니라 STATIC FILES_DIR 인 것 정확하게 확인할 것.
- 실제 프로젝트 폴더 구조에 어떻게 접근할 것인가에 대한 정보가 담겨 있음
-음

STATIC_ROOT
- 각 static 파일들을 한 곳으로 모을때... 즉 collectstatic 명령어를 수행할때 어떻게 경로를 만들것인가에 대한 정보를 담는 것. 

[참고](https://ssungkang.tistory.com/entry/Django-static-%ED%8C%8C%EC%9D%BC-%EB%8B%A4%EB%A3%A8%EA%B8%B0)



--------
