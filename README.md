# Better Ballard

### Fault-tolerant development cycle ;)
1. Develop site with `npm start`
1. When ready to deploy, build static assets with `npm run build`
1. Delete old resources and copy new resources with `aws s3 rm s3://betterballard.com/ --recursive && aws s3 cp ./dist s3://betterballard.com/ --recursive`
