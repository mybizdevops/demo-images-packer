# Demo Images

This repo contains all relevant files to build the required images for the myBIZDEVOPS demo.

To build the images yourself make sure [Packer](https://www.packer.io/) is installed. Then run the folloing commands in each subdirectory:

```
export AWS_ACCESS_KEY_ID='[YOUR AWS KEY ID]'
export AWS_SECRET_ACCESS_KEY='[YOUR AWS SECRET ACCESS KEY]'
export AWS_VPC_ID='[ID OF VPC TO BE USED]'
export AWS_SUBNET_ID='[ID OF SUBNET TO BE USED]'

packer build packer.json
```

Make sure to substitute the square backets in the command above.
