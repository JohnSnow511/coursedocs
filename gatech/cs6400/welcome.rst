Important Slides of DBMS Class
------------------------------


.. image:: https://dl.dropbox.com/s/zs4wvjb2ov95khf/Screenshot%202016-10-15%2018.33.47.png
   :align: center
   :height: 300
   :width: 450



.. image:: https://dl.dropbox.com/s/z7ak74epq01izbe/Screenshot%202016-10-17%2023.56.33.png
   :align: center
   :height: 300
   :width: 450


Case Study For Database Management
----------------------------------

* http://pe.sdt.gatech.edu/sites/default/files/GTPEgtonline_description.pdf


**Information Flow Diagram**

.. image:: https://dl.dropbox.com/s/ii5xi93odib6r6w/Screenshot%202016-10-18%2021.10.06.png
   :align: center
   :height: 300
   :width: 450

.. image:: https://dl.dropbox.com/s/cim93tdsezb9q0k/Screenshot%202016-10-18%2000.43.29.png
   :align: center
   :height: 300
   :width: 450


.. image:: https://dl.dropbox.com/s/7kn5hi23h32vj0r/Screenshot%202016-10-18%2000.52.47.png
   :align: center
   :height: 300
   :width: 450



.. image:: https://dl.dropbox.com/s/emt2cxxdkyayb3o/Screenshot%202016-10-18%2020.03.25.png
   :align: center
   :height: 300
   :width: 450


Data Formats - Beg, Steal, Borrow

* The Data formats for the Input and Output Diagram.
* These Data formats are applicable to the attribute types of the entities.


.. image:: https://dl.dropbox.com/s/yxydc1072m9nb9h/Screenshot%202016-10-18%2020.11.02.png
   :align: center
   :height: 300
   :width: 450

Constraints

.. image:: https://dl.dropbox.com/s/oph6v7prm2qvs5z/Screenshot%202016-10-18%2020.11.35.png
   :align: center
   :height: 300
   :width: 450

* Program the constraints into the application program.

* Each of the Task identified in the IFD diagram, we have to decide


.. image:: https://dl.dropbox.com/s/ouzqie532epjxk8/Screenshot%202016-10-18%2020.14.09.png
   :align: center
   :height: 300
   :width: 450

* Need of Mother Task.

**Example Task Decomposition**

.. image:: https://dl.dropbox.com/s/0dzyve2uy768151/Screenshot%202016-10-18%2020.23.48.png
   :align: center
   :height: 300
   :width: 450


.. image:: https://dl.dropbox.com/s/eezxnvvd9gvpjy2/Screenshot%202016-10-18%2020.24.48.png
   :align: center
   :height: 300
   :width: 450

**Example of View Profile Abstract Code**


.. image:: https://dl.dropbox.com/s/lbx64j2wo3eysyj/Screenshot%202016-10-18%2020.30.30.png
   :align: center
   :height: 300
   :width: 450

* No formal syntax for Abstract Code
* Penultimate Step before we write it in SQL


**Task Decomposition of Edit Profile**

.. image:: https://dl.dropbox.com/s/es675ja881vefez/Screenshot%202016-10-18%2020.36.02.png
   :align: center
   :height: 300
   :width: 450

**Example of Abstract Code**

.. image::  https://dl.dropbox.com/s/369gmt3u6x8ze5m/Screenshot%202016-10-18%2020.37.04.png
   :align: center
   :height: 300
   :width: 450

* Let's take a look at test decomposition for friend requests. The idea gain is that we have the forms that are the interface to the application.

* And our job is to now talk about the decomposition of the tasks that are necessary in order to tie these forms through the task into the database.

* If we did a closer analysis using the rule of thumb for task decomposition for this task we would arrive at the following result.

* The request friend test would be separate from the others. This task would update the database with a request and would support this form.

* The view, cancel, accept, and reject request task is the one that supports this form, and supports actions taken to the requests that are pending. It would end up being decomposed in two subtasks, view the request and then support the accept, reject, and cancel options. This subtask would update the friendship relationship type. This task would support the reading of user and regular user and friendship information.


.. image:: https://dl.dropbox.com/s/spwhz543wv1uxkb/Screenshot%202016-10-18%2020.47.14.png
   :align: center
   :height: 300
   :width: 450


Review of EER


Task Decomposition


.. image:: https://dl.dropbox.com/s/5qs7vlg2a66wm4r/Screenshot%202016-10-18%2020.57.35.png
   :align: center
   :height: 300
   :width: 450


.. image:: https://dl.dropbox.com/s/eqyblm1l649negk/Screenshot%202016-10-18%2020.58.44.png
   :align: center
   :height: 300
   :width: 450

View Profile Task Decomposition


.. image:: https://dl.dropbox.com/s/xk9ri6m2jmzuneh/Screenshot%202016-10-18%2021.00.16.png
   :align: center
   :height: 300
   :width: 450


**Edit Profile - 1**

.. image:: https://dl.dropbox.com/s/r7tqqxje6dj2u7y/Screenshot%202016-10-18%2021.00.54.png
   :align: center
   :height: 300
   :width: 450

**Edit Profile - 2**

.. image:: https://dl.dropbox.com/s/kr6jdshmi8lbndk/Screenshot%202016-10-18%2021.02.33.png
   :align: center
   :height: 300
   :width: 450

**Edit Profile - 3**

.. image:: https://dl.dropbox.com/s/xsdfgfjoakmn60d/Screenshot%202016-10-18%2021.03.53.png
   :align: center
   :height: 300
   :width: 450


**SQL Request Friendship**

.. image:: https://dl.dropbox.com/s/vm5m3nl8d9wk35z/Screenshot%202016-10-18%2021.04.58.png
   :align: center
   :height: 300
   :width: 450


**SQL View Pending Requests**

.. image:: https://dl.dropbox.com/s/hvv6cf5lurkpael/Screenshot%202016-10-18%2021.06.10.png
   :align: center
   :height: 300
   :width: 450


**SQL Accept, Reject, Cancel Friend Requests**

.. image:: https://dl.dropbox.com/s/ecs15vc3ac16btd/Screenshot%202016-10-18%2021.07.34.png
   :align: center
   :height: 300
   :width: 450

