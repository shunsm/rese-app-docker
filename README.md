## 開発環境構築について

Docker を用いて、LEMP 開発環境を構築できます。※ローカル環境のみ

## インストール方法

#### 任意のディレクトリに移動

```
$ cd [任意のディレクトリ]
```

#### Github から Clone

```
$ git clone https://github.com/shun0315/rese-app-docker.git
```

#### src ディレクトリを作成

```
$ mkdir src
```

#### Dockerfile からイメージをビルド

```
$ docker compose build
```

#### Docker コンテナの起動

```
$ docker compose up -d
```

#### app コンテナへ移動

```
$ docker compose exec app bash
```

####　 app コンテナ内でプロジェクトを作成

- 例

```
$ composer create-project "laravel/laravel=8.*" [プロジェクト名] --prefer-dist
```

- 例

```
$ git clone [任意のプロジェクト]
```
