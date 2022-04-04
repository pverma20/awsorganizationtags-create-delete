# awsorganizationtags-create-delete
This repo is used to tag and untag AWS organization resources such as Aws accounts


New Tag setup
aws organizations tag-resource --resource-id 489370314745  --tags Key=env,Value=qa Key=product-owner,Value=IT_Cloud Key=bill-to,Value=IT_Cloud Key=cost-center,Value=IT_Cloud Key=operation-group,Value=IT_Cloud


add new tag
aws organizations tag-resource --resource-id 489370314745  --tags Key=test,Value=test Key=tag2,Value=tag2


Untag/Remove/Delete any Tag
aws organizations untag-resource --resource-id Accountnumber  --tag-keys tagkey1 tagkey2 tagkey3 tagkey4 tagkey5
aws organizations untag-resource --resource-id 489370314745  --tag-keys Env newtag cost-center test Product-owner
