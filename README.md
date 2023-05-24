# ansible
앤서블 예제 

- 펄어비스에서 튜토리얼 문서로 작업하던 배포 예제입니다.
- 민감한 애용은 검수 후 제거하였습니다.
- LDAP 및 http+ssh 접속에 대한 내용도 같이 포함되어 있습니다.
- windows와 linux에 대한 예제가 별도로 표시됩니다. (사용 모듈이 다름)

```
📦pearlabyss
 ┣ 📂hosts
 ┃ ┣ 📂group_vars
 ┃ ┃ ┣ 📜all
 ┃ ┃ ┣ 📜linux
 ┃ ┃ ┗ 📜windows
 ┃ ┗ 📜static.yaml
 ┗ 📂playbooks
 ┃ ┣ 📜install_git-windows.yaml
 ┃ ┣ 📜install_jdk.yaml
 ┃ ┗ 📜install_svn-windows.yaml
 ```
