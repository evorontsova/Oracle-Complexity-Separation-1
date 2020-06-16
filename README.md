# Oracle-Complexity-Separation 
Students' project

- [Accelerated_Sliding_SVM_with_argmin](/Accelerated_Sliding_SVM_with_argmin.ipynb) — исправлено подсчет количества вызовов оракула, argmin в Катюше ищется аналитически, 
параметр регуляризации lambda = 0.1. Датасет: breast wisconsin (как в папке svm)

- [MS_acc_prox_without_grad_composite](/MS_acc_prox_without_grad_composite.ipynb) — не используется метод GradComposite, правильное количество вызовов оракула (получаются более лучшие результаты). 
Датасет: https://archive.ics.uci.edu/ml/datasets/Madelon (~500 семплов)

- [Variance_reduced_standard](/Variance_reduced_standard.ipynb) — реализован **Variance-reduced accelerated gradient method** (Alg 5.7 из "First-order and Stochastic Optimization
Methods for Machine Learning"). Датасет: https://archive.ics.uci.edu/ml/datasets/Madelon (~500 семплов)

- [Accelerated_Sliding_SVM_2k_dataset](/Accelerated_Sliding_SVM_2k_dataset.ipynb) — запуск на датасете с 2k семплами (Madelon) с исправленым подсчетом и argmin.

Также еще запускались много разных вариаций, (изменения по L, lambda, eps), Катюша 1 с разными вариантами tau1. Сильной разницы замечено не было.
