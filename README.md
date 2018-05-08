# dependencies
Contains dependencies.gradle file for simplify using in projects

Open build.gradle in your project and add line 

`apply from: 'https://raw.githubusercontent.com/kizup/dependencies/master/dependencies.gradle'`


After this you can implement dependencies in your modules like this

```
implementation libraries.supportAppCompat
implementation libraries.supportDesign   
implementation libraries.supportCardView
```
