```yml
[ERROR] [1] 2022-06-03 14:16:20.212 |||| LoggingFailureAnalysisReporter - 
Parameter 0 of constructor in com.package.package.service.logic.s65e040110SpringLogic required a single bean, but 2 were found:
```
- SpringLogic 부터 쫓아서 내려가다보면 implements 즉 MybatisStore 쪽에서 다른 객체를 implements로 구현하고 있어서 발생한 문제