# GitTest
学习使用git

//跳转到.ssj目录下
cd ~/.ssh/  
//创建
mkdir ~/.ssh  
//git配置用户名
git config --global user.name "zhangdong"
//git配置用户邮箱
git config --global user.email "zhangdong0921@139.com"  
//生成ssh-key (-t 是类型  -C 是备注，生成以备注结尾的ssh key)
ssh-keygen -t rsa -C "zhangdong0921@139.com"  


