#  Technical Documentation
Markdown ini adalah dokumentasi bagian Hacking dari Final Project Mata Kuliah Robot Autonomy. Direktori webots_machine_learning adalah clone dari [repository ini](https://github.com/joangerard/webots-thesis)

##  Webots Machine Learning
### 1. Instalasi dan Konfigurasi
#### 1.1. Instalasi Webots
Instalasi Webots dapat dilakukan dengan mengikuti [instruksi ini](https://cyberbotics.com/doc/guide/installation-procedure). Webots dapat diinstal pada sistem operasi Windows, Linux, dan Mac OS. Pada sistem operasi Windows dan Mac, Webots dapat diinstal dengan mendownload file instalasi dari [situs resmi](https://cyberbotics.com/#download). Pada sistem operasi Linux, Webots dapat diinstal dengan menggunakan perintah berikut:
    '''bash
    sudo apt-get install webots
    '''
#### 1.2. Instalasi Python dan Virtual Environment
Instalasi Python dapat dilakukan dengan mengikuti [instruksi ini](https://www.python.org/downloads/). Pada sistem operasi Windows, Python dapat diinstal dengan mendownload file instalasi dari [situs resmi](https://www.python.org/downloads/). Pada sistem operasi Linux, Python dapat diinstal dengan menggunakan perintah berikut:
    '''bash
    sudo apt-get install python3
    '''
Virtual Environment dapat diinstal dengan menggunakan perintah berikut:
    '''bash
    pip install virtualenv
    '''
Aktifkan virtual environment dengan menggunakan perintah berikut:
    '''bash
    source venv/bin/activate
    '''
#### 1.3. Instalasi Library Python
Pindah ke directory webots-project/controllers/pos-prediction dan install library python dengan menggunakan perintah berikut:
    '''bash
    cd webots-project/controllers/pos-prediction
    pip install -r requirements.txt
    '''
