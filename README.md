# config-server-repo

이 레포지토리는 Spring Cloud Config 서버를 위한 Repository로,  
마이크로 서비스들은 서비스가 실행될때, config-server를 통해, 해당 Repository에 있는 properties 파일을 Fetching합니다.
<br>  
[config-server repository 보러가기](https://github.com/wooriFisa-Final-Project-F4/config-server)

## Requirements

- 해당 레포지토리는 config-server를 통해 Encyrpt 되었습니다. 해당 레포지토리의 properties의 항목들을 decrypt하기 위해선 Encrypt Key가 필요합니다.
