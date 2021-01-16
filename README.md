# docker-compose-react
Reactの開発環境をdocker-composeで構築するためのテンプレートです.
中には，`npx craete-react-app app`コマンドで，作成された`app`

## 使い方
1. `git clone https://github.com/USHIken/docker-compose-react`
2. `cd docker-compose-react`
3. `docker-compose build`
4. `docker-compose up -d`

## npmライブラリ追加方法
1. `$`: `docker-compose run --rm node bash`
3. `#`: `npm install some-library`
4. `#`: `exit`
4. `$`: `docker-compose down && docker-compose up -d`

※もっと良さそうなやり方があったら教えて下さい
