# RealTime_PlaneAvionicSystem_2023
Simulating the communications between the sensors and actuators in an airplane system.

It uses RabbitMQ to communicate between threads.
By using RabbitMQ, one thread could wait and listen until a response is given by another thread, and act accordingly.
Thereby rendering the threads working together instead of it being totally independent from each other.
