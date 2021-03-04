# Packer

## Packer Validate

```
packer validate ami.json
```


## Packer Build
```
packer build \
    -var 'aws_access_key=' \
    -var 'aws_secret_key=' \
    -var 'aws_region=us-east-1' \
    -var 'subnet_id=subnet-0fa5ba21' \
    -var 'source_ami=ami-02fe94dee086c0c37' \
    ami.json
```
