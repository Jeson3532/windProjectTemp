"""# Проект прогнозирования временных рядов (TFT Model)


## 📌 Оглавление
1. [Установка окружения (Anaconda)](#1-установка-окружения-anaconda)
2. [Подготовка зависимостей](#2-подготовка-зависимостей)


---

## 1. Установка окружения (Anaconda)

Для стабильной работы рекомендуется использовать **Miniconda** или **Anaconda**.

1.  **Скачайте установщик:** [Anaconda.com](https://www.anaconda.com/download) или [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
2.  **Установите Anaconda**, следуя инструкциям установщика.
3.  **Откройте терминал:**
    * *Windows:* Anaconda Prompt (или PowerShell).
    * *Linux/macOS:* Обычный терминал.

4.  **Создайте новое виртуальное окружение:**
    ```bash
    conda create -n ml_forecast python=3.10 -y
    conda activate ml_forecast
    ```

---

## 2. Подготовка зависимостей

Требуется создать conda-окружение и установить требуемые пакеты.
1. conda create -n <название окружения> python=3.10 -y
2. conda activate <название окружения>
3. pip install -r <путь_к_requirements.txt>

Код тренировки и код инференса находятся в одном файле `main.py` для удобства тестирования.
