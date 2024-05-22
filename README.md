# Tigers crawler 구현
>대구대학교 타이거즈 화면 성적을 음성 혹은 텍스트로 반환해주는 프로그램


# 개발환경
>python,
>nodeJs,
>JavaScript,
>HTML

# selenium 실행을 위한 환경 설정
'''bash
brew install python
pip install selenium

실행시
python crawler.py
'''
# web 실행을 위한 환경변수 설정
'''bash
npm init -y
npm install express bcrptjs express-session body-parser
npm install mysql2 sequelize
'''

### DB 설정
'''sql
CREATE DATABASE mydatabase;
CREATE USER 'myuser'@'localhost' IDENTIFIED BY 'mypassword';
GRANT ALL PRIVILEGES ON mydatabase.* TO 'myuser'@'localhost';
FLUSH PRIVILEGES;
'''

### 실행 방법
'''bash
node server.js
'''
