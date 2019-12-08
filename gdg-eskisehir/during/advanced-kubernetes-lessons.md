# Advanced Kubernetes: Lessons Learned From Building a Managed Service

* Hüseyin Babal


## Notlar 

1. Kubernetes, ilk Google'da kullanılıyor, eski adı başka, daha sonra açık kaynak olarak paylaşılıyor
2. kendi datacenter'ınız varsa `kuberspray` kullanılabilir
3. `dev`, `staging`, `prod` izolasyonu çok önemli bir konu
4. namespaces in K8s
5. farklı, amacına uygun namespaces kullanımı önemli
6. `kubectx`
7. `kubectl`
8. `https://github.com/ahmetb`
9. `kubens`
10. `multi-tenancy`
11. `cluster seperation`
12. `monitoring of K8s`
13. `Prometheus`, K8s'te monitoring işini yapıyor
    1. `Prometheus-operator` ile kurmak daha kolay
14. `helm`, K8s'te paket yöneticisi
15. `Grafana`
16. `on-call` tools ile alert-managing
17. `Prometheus Federation`, 1'den fazla cluster'ı federe edip metrikler toplamak için
18. `Nginx Ingress`, loadbalancer
19. `service-oriented architecture (SOA)`, old name for `microservices`
20. microservices, insan topluluğuna benzer, aralarında dil/protokol olmalı, REST gibi.
21. `Github API` incele, detaylara bak, response'ları incele, detaylı linkler var
22. `K8s adaptation`
23. `.yml` file
24. Automation tools: `Github Actions`, `Jenkins`
25. `Docker Hub`
26. `canary deployment`, çok işinize yarayacak
27. `blue and green deployment`, daha pahalı bir seçenek
28. `logging in K8s`
    1. node level
    2. cluster level
29. `Humio` logging tool
30. `application performance management (APM)`
    1. NewRelic
    2. AppDynamics
    3. Zipkin
    4. Dynatrace
    5. Instana
31. `service mesh`