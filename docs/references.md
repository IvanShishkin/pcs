# Источники и смежные практики

## Классические работы

1. Conant R. C., Ashby W. R. *Every Good Regulator of a System Must Be a Model of That
   System*. International Journal of Systems Science, 1970, 1(2), 89–97.
2. Ashby W. R. *An Introduction to Cybernetics*. Chapman & Hall, 1956.
3. Kalman R. E. *On the General Theory of Control Systems*. 1960.

## Архитектура и эксплуатация

4. IBM. *An Architectural Blueprint for Autonomic Computing*. 2003/2006.
5. Google. *Site Reliability Engineering* и *The Site Reliability Workbook*.
6. Microsoft. *Azure Well-Architected Framework: Safe Deployment Practices*.
7. Argo CD и Flux: официальная документация по reconciliation и исправлению drift.

## Безопасность и управление AI

8. NIST. *AI Risk Management Framework 1.0*.
9. NIST SP 800-207. *Zero Trust Architecture*.
10. NIST SP 800-171. *Protecting Controlled Unclassified Information in Nonfederal
    Systems and Organizations*.

## Связь со смежными подходами

| Подход | Что PCS наследует | Отличие PCS |
|---|---|---|
| MAPE-K | Monitor, Analyze, Plan, Execute и Knowledge | Явные Authorize и Verify; объединение runtime и изменения продукта |
| GitOps | Desired/observed state, reconciliation и drift detection | Model шире инфраструктурной конфигурации |
| SRE/DevOps | Наблюдаемость, incident response, автоматизацию и release engineering | Единый агентный controller и путь до проверенного эффекта |
| OODA | Observe, Orient, Decide и Act | Явные policy, авторизация, model и проверка результата |
| Digital twin | Синхронизируемое представление объекта | Наличие механизмов решения, авторизации и воздействия |

