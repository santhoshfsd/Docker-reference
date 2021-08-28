### BuildKit 
- improves the performance
 
 ### build
 - `docker build --progress=plain . `
 
 ### New Docker Build secret information
- ` docker build --no-cache --progress=plain --secret id=mysecret,src=mysecret.txt .`