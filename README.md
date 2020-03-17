# Sleep Apnea Detection

This is the codebase for *Jayatilaka, Gihan, Weligampola, Harshana, Sritharan, Suren, Pathmanathan, Pankayaraj, Ragel, Roshan and Nawinne, Isuru, 2019. Non-contact Infant Sleep Apnea Detection. arXiv preprint [https://arxiv.org/abs/1910.04725](arXiv:1910.04725).*

The work was presented at [http://www.iciis.org/](ICIIS International Conference of Industrial Information Systems 2019). The proceedings will be made available soon.


You may cite this work as,
@misc{arxiv2019noncontact,
    title={Non-contact Infant Sleep Apnea Detection},
    author={Gihan Jayatilaka and Harshana Weligampola and Suren Sritharan and Pankayraj Pathmanathan and Roshan Ragel and Isuru Nawinne},
    year={2019},
    eprint={1910.04725},
    archivePrefix={arXiv},
    primaryClass={eess.SP}
}


## Objective
Developing a 100% non intrusive method for detecting sleep apnea in infants.

## Approach
A video feed is processed to detect the breathing pattern and then it is assessed for anomalies.

### Algorithms
Canny edge detection, Center of graviry tracking, subspace filtering, adaptive filtering, maxima detection.

### Hardware
Raspberry pi model 3 b
Raspberry pi camera

### Software
Python3, OpenCV

## People
[Gihan Jayatilaka](http://gihan.me) , [Harshana Weligampola](http://teambitecode.com/people/harshana) , [Suren Sritharan](http://teambitecode.com/people/suren) and [Pankayaraj Pathmanathan](http://teambitecode.com/people/pankayraj) developed this system as a course project for CO321 CO323 CO325.
The project was supervised by [Dr. Roshan Ragel](http://roshan.ragel.net) and [Dr.Isuru Nawinne](mailto:isurunawinne@gmail.com) .
The embedded system was developed by [Nuwan Jaliyagoda](http://teambitecode.com/people/nuwan) and [Anupamali Willamuna](http://teambitecode.com/people/anupamali).

## Acknowledgements
[Sanjaya Herath](mailto:slh.1995@gmail.com) provided the hardware components. [Dinidu Bhathiya](mailto:Dinidu.Bhathiya@syscolabs.com) provided a dataset. 

## For someone who wants to build up on this project
Please drop an email to [TeambiteCode@eng.pdn.ac.lk](mailto:bitecode@eng.pdn.ac.lk) or anyone mentioned in people section to obtain datasets or clarify technical details.

### Future work (ideas)
1. Identifying deafness in infants through behavioural analytics
2. Identify risky behaviour of the baby (trying to climb out of the cot)

