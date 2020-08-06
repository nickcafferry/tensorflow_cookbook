.. note::
   
   Neural Networks are very important in machine learning and growing in popularity due to the major 
   breakthroughs in prior unsolved problems.  We must start with introducing 'shallow' neural networks, 
   which are very powerful and can help us improve our prior ML algorithm results.  We start by introducing 
   the very basic NN unit, the operational gate.  We gradually add more and more to the neural network 
   and end with training a model to play tic-tac-toe.
   

神经网络学习井字棋
==============================

Given a set of tic-tac-toe boards and corresponding optimal moves, we train a neural network classification
model to play.  At the end of the script, we can attempt to play against the trained model.


引言
----------------
.. toctree::
       :maxdepth: 3
       
       /05_Nearest_Neighbor_Methods/01_Introduction/index

We introduce the concept of neural networks and how TensorFlow is built to easily handle these algorithms. 

------------

门运算和激活函数
---------------
.. toctree::
       :maxdepth: 3
       
       /05_Nearest_Neighbor_Methods/02_Working_with_Nearest_Neighbors/index


Now we have to introduce activation functions on the gates.  We show how different activation functions 
operate.


.. image:: 

下载本章 :download:`Jupyter Notebook </05_Nearest_Neighbor_Methods/02_Working_with_Nearest_Neighbors/02_nearest_neighbor.ipynb>`

-----

载入一层神经网络
--------------
.. toctree::
       :maxdepth: 3
       
       /05_Nearest_Neighbor_Methods/03_Working_with_Text_Distances/index


We have all the pieces to start implementing our first neural network.  We do so here with regression on
the Iris data set.

.. image:: 

下载本章 :download:`Jupyter Notebook </05_Nearest_Neighbor_Methods/03_Working_with_Text_Distances/03_text_distances.ipynb>`

-----------

载入多层神经网络
----------
.. toctree::
       :maxdepth: 3
       
       /05_Nearest_Neighbor_Methods/04_Computing_with_Mixed_Distance_Functions/index


This section introduces the convolution layer and the max-pool layer.  We show how to chain these together
in a 1D and 2D example with fully connected layers as well.

下载本章 :download:`Jupyter Notebook </05_Nearest_Neighbor_Methods/04_Computing_with_Mixed_Distance_Functions/04_mixed_distance_functions_knn.ipynb>`

-----------

使用多层神经网络
-------------
.. toctree::
       :maxdepth: 3
       
       /05_Nearest_Neighbor_Methods/05_An_Address_Matching_Example/index

Here we show how to functionalize different layers and variables for a cleaner multi-layer neural network.


下载本章 :download:`Jupyter Notebook </05_Nearest_Neighbor_Methods/05_An_Address_Matching_Example/05_address_matching.ipynb>`

-------------

图像处理的近邻法
-----------

.. toctree::
       :maxdepth: 3
       
       /05_Nearest_Neighbor_Methods/06_Nearest_Neighbors_for_Image_Recognition/index


The MNIST digit image collection is a great data set for illustration of how to perform 
k-Nearest Neighbors for an image classification task.

.. image::

下载本章 :download:`Jupyter Notebook </05_Nearest_Neighbor_Methods/06_Nearest_Neighbors_for_Image_Recognition/06_image_recognition.ipynb>`

-----------

本章学习模块
-----------

.. Submodules
.. ----------

*tensorflow\.zeros* 
^^^^^^^^^^^^^^^^^^^

.. automodule:: tensorflow.zeros
    :members:
    :undoc-members:
    :show-inheritance:

------

*tensorflow\.ones*
^^^^^^^^^^^^^^^^^^

.. automodule:: tensorflow.ones
    :members:
    :undoc-members:
    :show-inheritance:

-------------
