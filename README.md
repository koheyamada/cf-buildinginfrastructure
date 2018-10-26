# cf-buildinginfrastructure

## Description

## Usage
### vpc.yaml
```sh
$ aws cloudformation create-stack \
    --stack-name <スタック名> \
    --region <対象リージョン> \
    --template-body file://<テンプレートファイル名>
```

#### 例
```sh
$ aws cloudformation create-stack \
    --stack-name koh3i-nw \
    --region ap-northeast-1 \
    --template-body file://vpc.yaml
```

### securitygroup.yml
```sh
$ aws cloudformation create-stack \
    --stack-name <スタック名> \
    --region <対象リージョン> \
    --template-body file://<テンプレートファイル名>
```

*例*
```sh
$ aws cloudformation create-stack \
    --stack-name koh3i-nw \
    --region ap-northeast-1 \
    --template-body file://vpc.yaml
```
