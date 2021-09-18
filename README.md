# 创建应用外壳
## 1.准备应用
> 执行 ```ng new my-app --routing```  
> 对于既有应用，你必须手动添加 RouterModule 并在应用中定义 ```<router-outlet>```。
## 2.使用 CLI 自动创建一个应用外壳
> 执行 ```ng generate app-shell```
```
PS D:\workSpace\web\angular\pwa> ng generate app-shell
CREATE src/main.server.ts (298 bytes)
CREATE src/app/app.server.module.ts (590 bytes)
CREATE tsconfig.server.json (379 bytes)
CREATE src/app/app-shell/app-shell.component.html (24 bytes)
CREATE src/app/app-shell/app-shell.component.spec.ts (643 bytes)
CREATE src/app/app-shell/app-shell.component.ts (287 bytes)
CREATE src/app/app-shell/app-shell.component.scss (0 bytes)
UPDATE package.json (1521 bytes)
UPDATE angular.json (5090 bytes)
UPDATE src/main.ts (432 bytes)
UPDATE src/app/app.module.ts (715 bytes)
UPDATE tsconfig.json (527 bytes)
√ Packages installed successfully.
```
## 3.验证
> 执行```ng run my-app:app-shell:production```