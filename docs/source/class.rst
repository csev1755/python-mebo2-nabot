=====================
``mebo2_nabot.Robot``
=====================

The main class that represents a single Mebo 2.0 or Nabot AI robot toy and it's functions.

Movement
--------

Methods for moving the robot.

.. autoclass:: mebo2_nabot.Robot
   :members:
   :exclude-members: Camera, Command, Position, Speaker, Microphone, getInstance

.. autoclass:: mebo2_nabot.Robot.Command
   :members:
   :undoc-members:

.. autoenum:: mebo2_nabot.Robot.Position
   :members:
   :undoc-members:

Video and Audio
---------------

Methods for accessing the robot's camera, microphone, and speaker.

.. autoclass:: mebo2_nabot.Robot.Camera
   :members:

.. autoclass:: mebo2_nabot.Robot.Microphone
   :members:  
     
.. autoclass:: mebo2_nabot.Robot.Speaker
   :members:  
