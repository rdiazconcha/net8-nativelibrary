### Compile NativeLibrary.dll
dotnet publish /p:NativeLib=Shared --use-current-runtime

### Compile by using MinGW
gcc -o LoadLibrary .\LoadLibrary.c -lole32