References:

1. [Tooling](https://www.typescriptlang.org/docs/handbook/typescript-tooling-in-5-minutes.html)
2. [Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)

https://stackblitz.com/edit/typescript-jmm5e6?file=index.ts


Steps Done

1. npm init -y  // generates package.json
2. npx typescript --init  //generates tsconfig.json
    "rootDir": "src", 
    "outDir": "dist", 
3. src/index.ts
    const str:string = 'hello';
    console.log(str);
