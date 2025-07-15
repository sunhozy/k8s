# 1단계: nginx 이미지를 기반으로 설정
FROM nginx:alpine

# 2단계: build된 정적 파일들을 복사
COPY . /usr/share/nginx/html

# 3단계: nginx 설정 파일을 기본값 그대로 사용
# 필요 시 아래 주석 해제하여 커스텀 가능
# COPY nginx.conf /etc/nginx/nginx.conf

# 4단계: 80포트에서 서비스 실행
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
