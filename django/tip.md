# TIP
 - 아무 FK키가 없는 model을 맨 위에 만들어주는 것이 편하다.
 - 장고 클래스를 만들때 단수형으로 만들고, DB명은 META로 복수로 설정한다.
 - 장고 models에는 id필드가 자동으로 들어간다.
 - 쿼리문은 대문자로 쓰는게 좋다.

# 마이그레이션 
1. makemigrations (마이그레이션 파일 생성)
2. migrate (실제로 DB로 입력)


# 장고 폼



front : 객체
back : 딕셔너리

기능단위로 브렌치 나눠서 개발


git push origin [브렌치명]