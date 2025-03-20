# Docker基本コマンド

## Dockerイメージの操作

### イメージの一覧表示
```
docker images
```

### イメージの取得
```
docker pull <イメージ名>
```

### イメージの削除
```
docker rmi <イメージ名>
```

## Dockerコンテナの操作

### コンテナの一覧表示
```
docker ps
```

### 停止中のコンテナも含めた一覧表示
```
docker ps -a
```

### コンテナの起動
```
docker start <コンテナID>
```

### コンテナの停止
```
docker stop <コンテナID>
```

### コンテナの削除
```
docker rm <コンテナID>
```

## Dockerコンテナの実行

### 新しいコンテナの作成と実行
```
docker run -it --name <コンテナ名> <イメージ名>
```

### バックグラウンドでのコンテナ実行
```
docker run -d --name <コンテナ名> <イメージ名>
```
