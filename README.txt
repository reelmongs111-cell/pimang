# 피망머니 정보형 SEO 배포본

구성:
- index.html : 메인 페이지
- robots.txt : 크롤링 허용 + sitemap 위치 선언
- sitemap.xml : canonical URL 1개를 명시

배포:
1. 세 파일을 도메인 루트에 업로드
2. 브라우저에서 /robots.txt 와 /sitemap.xml 직접 열리는지 확인
3. Google Search Console에서 sitemap.xml 제출
4. URL 검사에서 https://akgame365.isweb.co.kr/ 색인 생성 요청

주의:
- sitemap에는 실제 canonical URL만 넣습니다.
- 동일한 내용을 URL만 바꿔 대량 생성하지 마세요.
- 실제 사이트가 다른 도메인으로 이전되면 canonical, Open Graph URL, JSON-LD URL, robots, sitemap의 도메인을 모두 동일하게 변경하세요.
