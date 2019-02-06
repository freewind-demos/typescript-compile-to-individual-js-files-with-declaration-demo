TypeScript Compile to Individual Js Files with Declaration Demo
===============================================================

```
npm install
npm run demo
```

关键点在于`include`中，将所有的ts文件（包括子目录）包含进来，
然后调用`tsc`为每一个文件生成相应的js和`.d.ts`文件。