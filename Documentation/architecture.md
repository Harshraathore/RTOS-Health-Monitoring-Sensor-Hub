# System Architecture

SensorTask --> Queue --> DisplayTask
                    |
                    v
               AlertTask

FreeRTOS scheduler manages task execution and communication.
