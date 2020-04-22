# icon-web

## Requirements

```sh
git clone git@github.com:jayunW/icon-web.git

cd icon-web
```

### Install lerna

[lerna](https://github.com/lerna/lerna)

```sh
yarn lerna
```

### Initialize lerna
```sh
yarn lerna init
```

independent

### dependencies

independent 각각의 모듈을 독립적으로 운영

```sh
yarn lerna init --independent

yarn lerna init -i
```

bootstrap 현재 lerna repo내의 패키지를 부트스트래핑

```sh
yarn lerna bootstrap

yarn lerna bootstrap --hoist // 각 패키지의 모듈을 모아서 루트에 딱 한번만 설치, 서로 의존하는 로컬 패키지들은 심볼릭 링크를 통해 연결
```

## Deployment

