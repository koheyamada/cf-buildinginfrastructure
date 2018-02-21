# cf-buildinginfrastructure

## VPCの作り方
    $ aws cloudformation create-stack \
        --stack-name <スタック名> \
        --region <対象リージョン> \
        --template-body file://vpc.yaml

