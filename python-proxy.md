- 프락시 환경에서 PIP 에서 오류가 발생하는 경우 환경변수 설정을 통해 해결
- HTTPS 인증서 오류가 발생하는 경우 환경변수 설정을 통해 
    ```
    HTTP_PROXY=http://192.168.0.1:8080
    HTTPS_PROXY=http://192.168.0.1:8080
    REQUESTS_CA_BUNDLE=C:\Users\admin\ca-bundle.crt
    ```
