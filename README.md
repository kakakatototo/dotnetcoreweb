# dotnetcoreweb

dotnet new web  
dotnet build  
dotnet run  

Kestrelの証明書、ポート周りでエラーになった場合  
For me the problem was resolved by running:  
dotnet dev-certs https --clean  
dotnet dev-certs https --verbose  
