# Angular 2 admin dashboard framework in ASP.NET Core

That project porting [ng2-admin] (https://github.com/akveo/ng2-admin) framework (use Angular 2, Bootstrap 4 and Webpack) to work with ASP.NET Core

<a target="_blank" href="http://akveo.com/ng2-admin/"><img src="http://i.imgur.com/QK9AzHj.jpg" width="600" alt="Sky Blue"/></a>

## Installation Guidelines

If you don’t have any of these tools installed already, you will need to:

* Download and install [.Net Core & Tooling] (https://www.microsoft.com/net/core)

* Download and install [git] (https://git-scm.com/)

* Download and install [nodejs] (https://nodejs.org)

Note: Make sure you have Node version >= 4.0 and NPM >= 3

Once you have those, you should install these globals with **npm install --global**:

* webpack
```
npm install --global webpack    
```    
* typescript
```
npm install --global typescript@2.0.0
```

* gulp
```
npm install --global gulp    
``` 

## Clone repository and install dependencies

You will need to clone the source code of ng2-admin-core GitHub repository:

```
git clone https://github.com/KhuongNtrd/ng2-admin-core.git
```

After the repository is cloned, go inside of the repository directory and install dependencies:

```
cd ng2-admin-core
npm install
```

Then run gulp **webpack** task

```
gulp webpack
```

Finally run dotnet command to start your local web app

```
dotnet run
```
Go to http://0.0.0.0:5000 or http://localhost:5000 in your browser.
