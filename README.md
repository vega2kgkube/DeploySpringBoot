### 로컬에서 DB와 SpringBoot 2개의 컨테이너 실행하기
#### Network 생성하기
* docker network 목록 확인하기
    ```
    docker network ls    
    ```
* docker network 생성하기
    ```
    docker network create --driver bridge msanet  
    ```
 