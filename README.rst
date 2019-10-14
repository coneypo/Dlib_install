Install Dlib in Windows/Ubuntu
##############################

Install pip
***********

Install latest pip3 for python3:

.. code-block:: bash

   python3 get-pip.py



In Windows
**********

Open Anaconda prompt in windows, and input follwing commands to install dlib:

.. code-block:: bash
 
   pip3 install dlib-19.1.0-cp35-cp35m-win_amd64.whl


In Linux
********

To install dlib, we recommand building from source code:

.. code-block:: bash

   git clone https://github.com/davisking/dlib
   python3 setup.py install


To install opencv, install from wheel:


.. code-block:: bash

   # for python3.5
   pip3 install opencv_python-4.1.1.26-cp35-cp35m-manylinux1_x86_64.whl
   
   # for python3.7
   pip3 install opencv_python-4.1.1.26-cp37-cp37m-manylinux1_x86_64.whl
