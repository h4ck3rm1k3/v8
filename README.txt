
How to build, from: https://developers.google.com/v8/build
on linux : http://code.google.com/p/v8/wiki/BuildingWithGYP
make dependencies
make native


Important types: 
 * JSFunction
 * SharedFunctionInfo
 * Object
 * Code

void InitializeFunction(JSFunction* function, SharedFunctionInfo* shared,   Object* prototype);
