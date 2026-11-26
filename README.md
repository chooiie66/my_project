# my_project
CI/CD를 위한 프로젝트. 간단한 대시보드를 구성

# 사용 소프트웨어
- app
    - 백엔드 : FastAPI, uvicorn
    - 프론트 : bootStrap 기반 adminlte 제품 4.0.0 버전
- DB 
    - mysql
- proxy
    - nginx
- 가상환경 구성
    - docker
        - Dockerfile, Docker-compose

# 구조
```
tree /F /A >> struct.txt
```
```
폴더 PATH의 목록입니다.
볼륨 일련 번호는 C0F3-E676입니다.
/
|   .gitignore
|   app.py
|   docker-compose.yml
|   README.md
|   struct.txt
|   
+---.github
|   \---workflows
|           deploy.yml
|           
+---app
|   |   Dockerfile
|   |   main.py
|   |   requirements.txt
|   |   
|   +---static
|   |   +---assets
|   |   |   \---img
|   |   |       |   *.jpg|*.png
|   |   |               
|   |   +---css
|   |   |       *.css
|   |   |       
|   |   \---js
|   |           *.js
|   |           
|   \---templates
|           index.html
|           login.html
|           
+---nginx
|       Dockerfile
|       web.conf
        

```