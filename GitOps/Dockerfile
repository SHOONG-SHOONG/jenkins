# Nginx 베이스 이미지 사용
FROM nginx:alpine

# 커스텀 index.html 복사
COPY index.html /usr/share/nginx/html/index.html

# 포트 설정 (기본 80)
EXPOSE 80

# 기본 명령 유지
CMD ["nginx", "-g", "daemon off;"]
