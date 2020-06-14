# <center>**Flask-Wow**</center>

[![Build Status](https://www.travis-ci.com/ganquan881205/Flask-Wow.svg?branch=master)](https://www.travis-ci.com/ganquan881205/Flask-Wow)

[中文文档](https://github.com/ganquan881205/Flask-Wow/blob/master/README_zh.md)

## What is Flask-Wow

Flask-Wow is a simple cli tool.

Similar to Django's built-in cli, can be used to create a new flask project or add a business module.

## Dependencies

- Python 3.6 +
- click 7.0 +

## Usage

- ### Install

```bash
sudo pip3 install flask-wow
```

- ### Uninstall

```bash
sudo pip3 uninstall flask-wow
```

- ### Createa new project

  In the directory where you want to create the project, execute the create command, set 'your_ project_name' with your project name.

  A '-v' or '--venv' option can tell the program to create a new  python virtual environment in the project folder.

```bash
flask-wow startproject your_project_name -v
```

- New project is created, the directory structure is roughly like this：

```bash
/your_project_name -> root folder
    run.py
    wsgi.py
    /requirements
        requirements_dev.txt
        requirements_prod.txt
    /your_project_name
        __init__.py
        config.py
        handlers.py
        /utils
        /apps
            /demo -> demo folder
                __init__.py
                views.py
                models.py
    /venv -> virtual environment
```

## ChangeLog

- 0.1.0   project init.

## TODO

- Add Unit Test
- Add new command to create a new business module
- Complete demo examples
- optimization

## Contribution

If you have any ideas or suggestions about this project，please feel free to fork、open issues and send pull requests.
Or send e-mail to cove@happyeyez.com
