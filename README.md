# nx-serverless-monorepo

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
