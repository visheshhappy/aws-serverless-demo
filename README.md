install serverless using command
npm install serverless --global

sls invoke local -f hello

send some event like this :
sls invoke local -f hello -d '{\"key\":\"vishesh\"}'

sls deploy --stage prod

sls deploy --stage prod -f hello

sls remove

To install offline plugin use : 
npm install --save-dev serverless-offline 

sls offline

get last 5 min logs : 
sls logs -f add -s prod --startTime 5m


tail latest logs
sls logs -f add -s prod --tail
