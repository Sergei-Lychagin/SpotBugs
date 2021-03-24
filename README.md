### Задание
+ Настроить goal check в фазу verify
  
 Так как `spotbugs:check`запускается по умолчанию в фазе verify жизненного цикла maven
 то цель можно не прописывать в pom.xml таким образом:
 ```<execution>
<id>check</id>
<phase>verify</phase>
 <goals>
 <goal>check</goal>
 </goals>
 </execution>