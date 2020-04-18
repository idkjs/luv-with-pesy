# luv-with-pesy


[![CircleCI](https://circleci.com/gh/yourgithubhandle/luv-with-pesy/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/luv-with-pesy/tree/master)


**Contains the following libraries and executables:**

```
luv-with-pesy@0.0.0
│
├─test/
│   name:    TestLuvWithPesy.exe
│   main:    TestLuvWithPesy
│   require: luv-with-pesy.lib
│
├─library/
│   library name: luv-with-pesy.lib
│   namespace:    LuvWithPesy
│   require:
│
└─executable/
    name:    LuvWithPesyApp.exe
    main:    LuvWithPesyApp
    require: luv-with-pesy.lib
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x LuvWithPesyApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
