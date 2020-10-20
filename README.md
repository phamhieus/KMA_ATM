# KMA_ATM
## Cach miragtion database: 
### Cac cau lenh:
dotnet ef database update
dotnet ef migrations add InitialProject
dotnet ef migrations add InitialDatabase --startup-project 'DemoShop.Web'
dotnet ef database update --startup-project 'DemoShop.Web'
