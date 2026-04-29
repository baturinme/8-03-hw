# Домашнее задание к занятию "GitLab" - Батурин Максим

## Задание 1

![Скриншот развёрнутого проекта в GitLab](img/Task1_1.png)
![Скриншот созданного Runner](img/Task1_2.png)

## Задание 2
### Файл .gitlab-ci.yml
```yaml
stages:
  - test

test:
  stage: test
  tags:
    - docker
  image: alpine:latest
  script:
    - echo ""

![Скриншот активного Runner в GitLab](img/Task2_1.png)
![Скриншот успешно выполненного Pipeline](img/Task2_2.png)
