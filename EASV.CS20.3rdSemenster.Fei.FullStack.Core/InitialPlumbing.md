### Full Stack 

# Back End
## 1. Initial Plumbing 
- Put into C drive

### Clean Architecture

#### Core 
- which contain about Core and Domain
- Core contain Modle and IService
- Domain contain Service and IRepository

[Architecture](EASV.CS20.3rdSemenster.Fei.FullStack.Core/Architecture.drawio)  


#### Infrastructure
- Containing about DataAccess and Security
- DataAccess contain Repository  

  
#### Presentation  
- Contain WebApi

## 2. Use TDD ( Test Driven Development)
### 2.1 make Core Test Project

- Create solution folder : Core-Test
- Create new project : EASV.CS20.3rdSemenster.Fei.FullStack.Core.Test
- Using by xUnit
- Now if we just run the unit test, it will success by doing nothing but prove we create a right test project.



### 2.2 Make a Test class to test models

- Fx. ProductTest
-  