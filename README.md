# D_WAVE
This exercise deals with the D-wave example of a "Reservoir Management". Here a problem's description from D-Wave:

Water reservoir levels must be carefully controlled to satisfy consumer demand while maintaining minimum water levels. To satisfy this demand and maintain at least a minimum level of water in the reservoir, pumps can be operated to provide water flow into the reservoir. To operate these pumps there is a cost, and we would like to choose which pumps to use throughout the day in order to minimize cost. In this demo scenario, we have seven pumps that can be operated on 1-hour intervals throughout a 24-hour day.

The challenge is coped on D-wave using a BQM. In this notebook instead the problem was solved using a CQM. The results obtained with this model show a better performance (in terms of minor operating cost of the pumps), if compared with the BQM used by the authors.

**This section has been coded for performance on problems of the industrial scale supported by Leap’s quantum-classical hybrid solvers.**

The previous implementation was written for readability, this comes at the cost of speed.

In this version we wiilbe skipping symbolic construction altogether, working directly with variable labels and a QM object.
