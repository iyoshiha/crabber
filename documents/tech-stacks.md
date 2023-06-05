# tech stacks

- docker
- twirp
- protocol buffers
- DynamoDB
- git actions 
- SQLBoiler
- wire
- Golang
- MySQL
- ci/cd
- github actions 
- datadog
- aws EventBridge
- aws ECS
    - EventBridge trigger 
- swagger: open api 
    - repository/src/YAML (end point, schemeごとに分割する)
            YAMLファイルはsrc/以下に格納
    - $ docker-compose up -d
            docker-composeでOpenAPIレンダラーのコンテナとYAMLファイルをマージするコンテナが起動する。
            ファイルを編集して保存すると、ファイルの更新を検出して自動的にdocs/swagger.ymlにマージされる。
            http://localhost:8080アクセス編集結果を閲覧するできるようにする。
