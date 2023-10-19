# Project Name
> Alat penerjemah ke bahasa isyarat

## Table of Contents
* [Deskripsi umum](#deskripsi-umum)
* [Teknologi yang digunakan](#technologies-used)
* [Fitur](#fitur)
* [Setup](#setup)
* [Usage](#usage)
* [Contact](#contact)



## Deskripsi umum
- Alat penerjemah ke bahasa isyarat adalah perangkat atau aplikasi yang dirancang untuk membantu dalam komunikasi dengan individu yang menggunakan bahasa isyarat. Bahasa isyarat adalah bentuk komunikasi visual dan gestur yang digunakan oleh individu yang memiliki gangguan pendengaran atau sulit untuk berkomunikasi.
- Alat penerjemah ke bahasa isyarat bertujuan untuk memecahkan beberapa masalah komunikasi yang dihadapi oleh individu yang menggunakan bahasa isyarat, terutama mereka yang memiliki gangguan pendengaran atau kesulitan berkomunikasi secara verbal. 



## Teknologi yang digunakan
- Phyton
- HTML
- Shell


## Fitur
- Mengubah suara menjadi bahasa isyarat yang bisa dimengerti orang tuli



## Setup
Django==4.0.1
django-environ==0.8.1
gunicorn
nltk``


## Usage
    """Django's command-line utility for administrative tasks."""
import os
import sys

credentials_json_key = "key.json"
os.environ["GOOGLE_APPLICATION_CREDENTIALS"] = credentials_json_key

def main():
    """Run administrative tasks."""
    os.environ.setdefault('DJANGO_SETTINGS_MODULE', 'SpeechToSign.settings')
    try:
        from django.core.management import execute_from_command_line
    except ImportError as exc:
        raise ImportError(
            "Couldn't import Django. Are you sure it's installed and "
            "available on your PYTHONPATH environment variable? Did you "
            "forget to activate a virtual environment?"
        ) from exc
    execute_from_command_line(sys.argv)


if __name__ == '__main__':
    main()



## Perkembangan


Room for improvement:
- Improvement to be done 1
- Improvement to be done 2

To do:
- Feature to be added 1
- Feature to be added 2







