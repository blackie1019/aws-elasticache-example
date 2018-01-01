# aws-elasticache-example
AWS elasticache sample code

## Setup node.js in Amazon Image ##

當我們用 ssh/putty 工具連線進入 EC2 內後立即做環境更新並安裝 nodejs：

  sudo yum update
  curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.6/install.sh | bash
  . ~/.nvm/nvm.sh
  nvm install 6.11.5
  node -e "console.log('Running Node.js ' + process.version)"