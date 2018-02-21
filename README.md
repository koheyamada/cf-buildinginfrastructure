# cf-buildinginfrastructure

## 新規作成
    $ aws cloudformation create-stack \
        --stack-name <スタック名> \
        --region <対象リージョン> \
        --template-body file://<テンプレートファイル名>

例
    $ aws cloudformation create-stack \
        --stack-name koh3i-nw \
        --region ap-northeast-1 \
        --template-body file://vpc.yaml

