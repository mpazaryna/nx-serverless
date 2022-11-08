# nx-serverless-monorepo

## Day One Commands

yarn i
npx nx run hello:deploy --stage=dev
npx nx test hello

npx nx workspace-generator serverless hello
npx nx g @nrwl/node:lib --skipBabelrc --tags lib util
npx nx run hello:deploy --stage=dev
npx nx run hello:remove --stage=dev
npx nx:run-commands hello:deploy --stage=dev
npx nx run hello:remove --stage=dev
yarn nx run hello:deploy --stage=dev
npx nx run hello:deploy --stage=dev
npx nx test hello
npx nx test util

## Deployed Hello Stack

https://qur5njxefi.execute-api.us-east-1.amazonaws.com/dev/hello
