# security-test-xss-15-05-2025
teste de xss

```bash
# scripts pra rodar
docker build -t lab-xss .

docker run -d -p 8080:80 lab-xss

## acessar: site/reflected.html?nome=%3Ciframe%20src=%22https://js-dos.com/games/doom.exe.html%22%20width=%221780%22%20height=%22900%22%20framemborder=%220%22%20scrolling=%22yes%22%20allowfullscreen%3E
```