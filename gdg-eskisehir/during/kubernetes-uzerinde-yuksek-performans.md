# Kubernetes Üzerinde Yüksek Performans

* Metin Seylan


## Notlar

1. `Scotty`, Uber'in İstanbul'daki motorsiklet versiyonu
2. Backend'te 24 developer çalışıyor
3. `Spring Framework` kullanarak, örneklerle temel kavramlardan bahsediyor
4. `dependency injection`
5. `application context`
6. `ayağa kaldırmak`, bağımlılıkları düşünerek, sırasıyla kurmak
7. `repository interface`
8. `feign client`
9. simple pipeline: code, test, compile, deploy, run
10. `runtime reflection`
11. bootup problem in K8s
12. pods in K8s are clusters
13. horizontal pod autoscale
14. microservice reality = micro + service
15. reflection-free frameworks: Micronaut, Quarkus (compile time'da ayağa kaldırırlar, runtime'da değil), ahead of the time compilation (AoT)
16. `HTTP 3.0`
17. gRPC, framework on HTTP 2.0, for microservices, giving stream
18. JSON to Proto (79 kb to 19 kb)
19. code generating, 12 languages, gRPC Probe file, Profoc code generator
20. `reactive programming` Java'da kullanılıyor, Node zaten kullanıyor