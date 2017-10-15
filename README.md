# Virtual Gyroscope
Xi Han, Xu Zhang, Zhanming Zhang

## Abstract
Gyroscope is one of the major energy consumer among the IMU sensors. The optimization of energy cost of such senser is of huge interest because IMU sensers have broad applications, such as on cell phones to faciliate user interface, on UAVs to help navigate and of course, robotics. Most of the applications depend on battaries or even passively-harvested energy. In this work, we will seek for possibilities to duty-cycle the gyroscope when its result can be reliably approximated by data from sensors that consume less power, such as accelerometers and magnetometers. In specific, we are interested in under what condition the approximation is and is not reliable, and why. We will start from this paper[<sup>1</sup>][1] of Baptiste et al.

## Proposal
Baptiste and his colleagues have proposed two method for emulating a gyroscope with an accelerometer and a magnetometer. Base on their work, our tentitive first step of this work is to implement and compare the two methods. In particular, we'd like to investigate in what scenario which method works better, and also the implementation subtlties of each method.

After that, we will compare the data from the emulation with the data from a true gyroscope. By analyzing the data, we'd like to investigate any possibility that we can create a model for the accuracy of the emulation given different conditions so that we may duty-cycle the gyroscope when the accuracy is high. 

After we come up with a model, we will then implement the model on a real platform and see how it works! More to come when we reach there.

## Schedule

| Week No. | Objective                           |
|----------------------------------------------- |
| Week 3   | Proposal and Schedule               |
| Week 4   | Implementation of the algorithms    |
| Week 5   | Implementation of the algorithms    |
| Week 6   | Modeling                            |
| Week 7   | Modeling                            |
| Week 8   | On-board implementation and testing |
| Week 9   | On-board implementation and testing |
| Week 10  | Conclusion, report and demo         |

[1]: https://hal-enpc.archives-ouvertes.fr/file/index/docid/826243/filename/AccelerometerAndMagnetometerBasedGyroscopeSensorAndTransducteurJournal.pdf
