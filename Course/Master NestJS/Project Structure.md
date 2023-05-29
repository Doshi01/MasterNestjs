![](/Users/linling/Library/Application Support/typora-user-images/image-20230529223923964.png)



1. Application starting point is the main.ts file that bootstraps the application
2. Nest apps consists of modules, always having at least 1 main module, by default called the AppModule
3. The module is comprised of controllers, services, entities and other smaller building blocks
4. Modules are defined in their Own module files, and the class decorator @Module is used to describe them