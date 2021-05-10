# Simple dotnet API + MongoDB for CoronaVirus tracking

<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" /> <img src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white" /> <img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>

### CoronaVirus Tracker API built on ASP.NET + C# + MongoDB as a prerequisite of (Digital Innovation + Take) FullStack Bootcamp!

Get method for https://localhost:5001/infectado

Returns a list with all infected people

Post method example for https://localhost:5001/infectado

```json
{
	"dataNascimento": "1990-03-01",
	"sexo": "M",
	"latitude": -23.5630994,
	"longitude": -46.6565712
}
```
PS: change appsettings.json with your string connection
