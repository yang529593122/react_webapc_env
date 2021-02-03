#####    环境运行
yarn start   本地环境 
yarn build:test 测试环境 
yarn build:prod 生产环境

#####  多种环境 api 配置
process.env.REACT_APP_ENV    值为 dev 是本地开发环境  和 测试环境   prod 生产环境

##### 目录结构描述
├── config                      // 配置   
├── public                      // html模版  
├── scripts    
│    └── build.js               // 打包文件    
│    └── start.js               // 本地启动文件    
│    └── test.js                // 测试启动文件    
├── src                         // 项目开发目录    
│    └── api                    // 请求文件目录    
│    └── components             // 通用组件目录    
│    └── pages                  // 页面组件    
│    └── routes                 // 路由目录     
│    └── static                 // web静态资源             
│    └── store                  // redux 目录    
│    └── tools                  // 工具文件目录    
│    └── App.js                 // app 容器    
│    └── index.js               // 项目入口文件    
├── package.json    


