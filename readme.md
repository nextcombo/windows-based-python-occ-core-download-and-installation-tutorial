# Windows-based Python OCC-Core Download and Installation Tutorial

PythonOCC-Core Installation and Configuration Full Guide - Part 1: Project Overview and Core Languages

PythonOCC-Core Installation and Configuration Full Guide

I. Project Overview and Core Languages

Project Overview

PythonOCC-Core is a Python toolkit specifically designed for 3D geometric applications in CAD/BIM/CAM. It boasts powerful capabilities for 3D modeling and data interaction, providing robust support for development work related to CAD, PDM, PLM, and BIM. This toolkit is built on the OpenCascade Technology modeling kernel, allowing developers to easily call almost all C++ classes from OpenCascade with Python.

Core programming languages

PythonOCC-Core development is primarily centered around the Python language, while it also relies on C++ and SWIG (the tool used to generate Python interfaces).

II. Key Technologies and Frameworks Used in the Project

Key technology

OpenCascade Technology (OCCT): An open-source 3D modeling kernel with rich geometric and topological operations, providing solid underlying support for PythonOCC-Core.

SWIG: As a software development tool, it can cleverly encapsulate C++ code into Python interfaces to achieve seamless integration between the two languages.

Framework

Python GUI frameworks: including Tkinter, PyQt5/6, PySide2/6 and wxPython. These frameworks can be used to implement 3D visualization functions, providing users with intuitive interactive interfaces.

Web Browser 3D Visualization Framework: Three.js and X3DOM can realize 3D visualization in Web browsers, facilitating users to view and operate on different platforms.

Interactive Development Framework: Jupyter Notebook provides a user-friendly interactive development environment for 3D visualization and related development work.

III. Preparation and detailed process for project installation and configuration

Preparation

Before officially starting the installation journey, please ensure that your system has installed the following software:

Python 3.7 and above

Conda (recommended to use Anaconda3 or Miniconda3)

Git (used for cloning project repositories and fetching the latest code)

Detailed installation process

Step 1: Create a Conda environment

First, create a new Conda environment in the command line and activate it:

conda create --name pyoccenv python=3.10

conda activate pyoccenv

Step 2: Install PythonOCC-Core

Install PythonOCC-Core using Conda. Since the precompiled package of PythonOCC-Core depends on third-party libraries in the conda-forge channel, use the following command for installation:

conda install -c conda-forge pythonocc-core=7.8.1

Step 3: Verification of Installation

After installation, to confirm whether PythonOCC-Core has been successfully installed, you can enter the following command in the command line:

python -c "import OCC; print(OCC.__version__)"

If the installation is successful, the command line will output the version number of PythonOCC-Core. If the installation fails, it's not a problem; you can try using the method provided in gitee.com/FIRC/installservice/blob/master/pythonocc-core.md to directly install it.

Step 4: Run the example code

To further verify the correctness of the installation, you can download the example code from the GitHub repository of PythonOCC-Core and run it. The specific operation is as follows:

git clone pythonocc-core.git

cd pythonocc-core/examples

python example_script.py

Optional steps: Build from source code

If you have special requirements and need to build PythonOCC-Core from source code, you can refer to the INSTALL.md file in the project repository. This file contains detailed build instructions, and following the instructions step by step will complete the build.

IV. Summary

Through the above series of steps, you have successfully installed and configured PythonOCC-Core. Now, you can fully leverage its advantages and embark on the exciting journey of 3D modeling and data exchange development, starting a fantastic 3D development journey.


## Payment

Here is a pay link on Stripe ( https://buy.stripe.com/3cs8yP7sY87d0vu9AB ). Please contact me lonlonago@foxmail.com after funding $89, and I will send you a complete data files , thank you!

![111.png](111.png)
