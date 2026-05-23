Examples
========

Code examples for the module are available in ``examples/``

Install Example Code Dependencies
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: sh

   pip install -r examples/requirements.txt

Move the Robot
~~~~~~~~~~~~~~

.. code-block:: python

   import mebo2_nabot

   robot = mebo2_nabot.Robot()
   robot.forward(steps=2)
   robot.arm_up(steps=2)

Retrieve Joint Positions
~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block:: python

   import mebo2_nabot

   robot = mebo2_nabot.Robot()
   print(robot.get_joint_positions())
