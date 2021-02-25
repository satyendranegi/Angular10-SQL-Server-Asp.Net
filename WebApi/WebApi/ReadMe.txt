Datatbase

--create table dbo.Employee(
--EmployeeId int identity(1,1),
--EmployeeName varchar(500),
--Department varchar(500),
--DateOfJoining date,
--PhotoFileName varchar(500)
--)

--insert into dbo.Employee values('satyen','IT','2020-06-01','ssn.png')

select * from dbo.Employee

------------------------------------------------------------------------
--create table dbo.Department(
--DepartmentId int identity(1,1),
--DepartmentName varchar(500)
--)

select * from Department

--insert into Department values('Support')
-------------------------------------------------------------------------------------------------------------
Install-Package Microsoft.AspNet.WebApi.Cors