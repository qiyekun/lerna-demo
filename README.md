# lerna-demo


mkdir lerna-demo

cd lerna-demo && lerna init


cd packages && mkdir my-app-proxy && cd my-app-proxy && npm init -y


cd ../../ && lerna bootstrap


lerna publish
