To perform the tests for the calculcation of the throughput in Transactions Per Second (TPS), we used BASH to cycle JavaScript code towards different nodes.

The bash script is [TPS_bash_script.sh](https://github.com/papersblindsubmissions/BEV/blob/master/tests/TPS_bash_script.sh).

This script mainly run JavaScript code using node.js and calculate the time elapsed to perform its execution.

The number of repetition is set using the $COUNT variable.

Three different pairs of cryptography keys are used, associated to DistrictA, DistrictB and DistrictC.

Each JavaScript script is run using one of these key pairs.
