# AsciiArtify Kubernetes Deployment

## Завдання
Допоможіть команді у підготовці порівняльного аналізу трьох інструментів для розгортання Kubernetes кластерів в локальному середовищі — minikube, kind та k3d. Візьміть до уваги ризики, що можуть виникнути з ліцензуванням Docker та розгляньте можливість застосування альтернативи Podman. Після ознайомлення з інструментами, підготуйте документ, який включатиме наступні пункти:

- **Вступ:** Опис інструментів та їх призначення.  
- **Характеристики:** Опис основних характеристик кожного інструменту, таких як підтримувані ОС та архітектури, можливість автоматизації, наявність додаткових функцій, таких як моніторинг та керування Kubernetes кластером.  
- **Переваги та недоліки:** Опис переваг та недоліків кожного інструменту, таких як легкість використання, швидкість розгортання, стабільність роботи, наявність документації та підтримки спільноти, складність налаштування та використання.  
- **Демонстрація:** Коротка демонстрація рекомендованого Вами інструменту з використанням прикладу, такого як розгортання застосунку «Hello World» на Kubernetes.
- **Висновки:** Заключення та рекомендації щодо використання кожного інструменту в PoC для стартапу.  

Інженер повинен провести практичне ознайомлення з кожним інструментом та записати коротке демо, щоб показати основні можливості рекомендованого інструменту. На базі цього задокументувати висновок, з порівняльним аналізом кожного інструменту, що допоможе зробити відповідний вибір для розгортання локального Kubernetes кластеру для PoC стартапу "AsciiArtify".

## Introduction
AsciiArtify, a startup focused on developing a new software product for transforming images into ASCII art using Machine Learning, faces the challenge of selecting the right tool for local Kubernetes cluster development. The team, comprised of two young programmers with expertise in software development but lacking DevOps experience, is considering three options: minikube, kind and k3d.

## Characteristics
### Minikube
- `Supported OS and Architectures:` Works on multiple operating systems, including Windows, macOS, and Linux. Supports various architectures.  
- `Automation Capability:` Offers automation for cluster creation and management.
- `Additional Features:` Suitable for local development and testing. Concerns arise regarding scalability limitations.  

### Kind (Kubernetes IN Docker)
- `Supported OS and Architectures:` Compatible with Windows, macOS, and Linux. Works within Docker containers.  
- `Automation Capability:` Allows the creation of local Kubernetes clusters in Docker containers.  
- `Additional Features:` Considered for local testing purposes.

### k3d
- `Supported OS and Architectures:` Works on multiple operating systems. Uses Rancher Kubernetes Engine (RKE) in Docker containers.
- `Automation Capability:` Facilitates quick creation and testing of Kubernetes clusters in Docker containers.
- `Additional Features:` Chosen for preparing Proof of Concept (PoC).

### Characteristic



[![k3d Demo](https://asciinema.org/a/gwmbcxL3smcfA7pyMjSpGikFw.svg)](https://asciinema.org/a/gwmbcxL3smcfA7pyMjSpGikFw)