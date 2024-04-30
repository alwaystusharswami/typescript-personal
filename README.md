# typescript-personal
# for install 
* npm install typescript

for  global 
* npm  i typescript -g

# compile in js 
tsc <--FILE_NAME-->

# config file 
tsc --init 

### change in config file
1. if you want to compile  files then search rootDir in config file of typescript and give path for folder

```
 "rootDir": "./",    // give path here
 
```
2. if you want to store save ts files in one folder then search outDir in config file of typescript and give path for folder
``` 
 "outDir": "./",       // give path here 

```

3. if only particular one folder then in end of config file add this code 
``` 
"include":[
    "src"
]

```
 ==  now only src file will be change in js .


 4. if error in ts file and it access to convert  file into js, big issues in js file so we fix by uncomment on line that's means if error in ts file don't compile or convert in js file
 ```
    "noEmitOnError": true,                     // uncomment this line
  ```

