# Resume_Classifier

H1 A simple Resume Parser used for extracting information from Resumes/CVs

Installation
pip install pyresparser

GUI
Django used
Easy extraction and interpretation using GUI
For running GUI execute:

  python resume_parser/manage.py makemigrations
  python resume_parser/manage.py migrate
  python resume_parser/manage.py runserver

Visit 127.0.0.1 to view the GUI

Result
The module would return a list of dictionary objects with result as follows:

[
    {
        'education': [('B.Tech', '2022')],
        'email': 'en18cs301231@medicaps.ac.in',
        'mobile_number': '8982556535',
        'name': 'Sanskar Gupta',
        'skills': [
            'Flask',
            'Django',
            'Mysql',
            'C',
            'Css',
            'Html',
            'Js',
            'Machine learning',
            'C++',
            'Algorithms',
            'Github',
            'Python',
        ]
    }
]
