# modpacks

## Nebulaの使い方

```sh
cd Nebula
```

## 環境変数 (例)
```env
JAVA_EXECUTABLE=c:\Program Files\Java\jdk-22\bin\java.exe
ROOT=C:\ghq\github.com\UzushikaMinecraft\modpacks
BASE_URL=https://raw.githubusercontent.com/UzushikaMinecraft/modpacks/master/
HELIOS_DATA_FOLDER=C:\Users\iamta\AppData\Roaming\.uzushikalauncher
```

## 依存関係のインストール
```sh
npm i
```

## ModPackの新規作成 (例)
```sh
npm run start -- generate server Foo 1.20.1 --forge 47.3.11
```

## distribution.jsonの更新
```sh
npm run start -- generate distro
```