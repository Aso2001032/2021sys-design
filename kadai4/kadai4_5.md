```uml
@startuml
start
if (weather=0) then (true)
  :快晴です;
elseif (weather=1) then(ture)
  :曇りです;
elseif (weather=2) then(true)
  :雨です;
else (false)
  :不明です;
endif
stop
@enduml
```
