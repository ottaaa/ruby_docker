docker image のビルド  
`$ docker build . -t ruby:local `  

ruby ファイルの実行  
`$ docker run --rm --name ruby -it ruby:local  ruby main.rb ` 
