This code is developed to serialize and deserialize data.

As per requirements, deserialization of buffer data from external file is done and the packet structure is populated and printed.

Additionally, serialization of the populated packet is done and stored in a packet buffer.

The main.h file is included in the inc folder. 

Unit testing has been done using CUnit testing framework to confirm the functionality.
To install CUnit:
> sudo apt-get install libcunit1 libcunit1-doc libcunit1-dev

COMPILATION STEPS:
For normal code compilation type in terminal:
> make build

To run the code:
> ./build

To clean .o and executable files:
> make clean

For UnitTest (make build must be done before this):
> make run

To run UnitTest:
> ./run

To clean unit test executable:
> make uclean
