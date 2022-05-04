1.规范代码（代码规范 + 风格统一） prettier + esLint 开发阶段规范代码
 .prettierrc:{ 
     "tabWidth":2, 
     "printWidth":80, //最大行数 
     "semi":true //保留分号 
     "singleQuote": true //是否使用单引号 
     } 
     eslint-plugin-prettier //链接prettier和eslint 
     eslint-config-prettier //并解决冲突

2.gitcommit 之前通过husky/list-staged进行代码是否规范进行校验

3.gitcommit通过 （commitlint-cli/config | Fix feat）对cmmit信息进行校验（cmmit信息规范化） commitlint-commitizen可以增加自己的校验规则

4.can i use 查看es10+兼容性，配置plugin兼容语法