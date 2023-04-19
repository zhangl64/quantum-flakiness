# Identifying Flakiness in Quantum Programs

## Introduction
In the table below, 12 different repositories are examined, which represent the creation of the flaky tests in quantum programs. Moreover, we list links of flaky tests in quantum projects as well as the root causes of flakiness, and we provide the categories for fixing these different flaky tests. Our goal is to create a view for better understanding and easier access to the dataset so that others can reproduce our findings.
## quantum-flakiness
|  Repository |   Bug-Report-Link  |  Pull-Request-Link | Categories-of-Flaky-Test |      Categories-of-Fix            |
|    :---     |    ---:            |  ---:              |         :---             |              :---                 |
| Qiskit-Terra | [#6105](https://github.com/Qiskit/qiskit-terra/issues/6105) | [#6399](https://github.com/Qiskit/qiskit-terra/pull/6399) | Parallization | Multithreading (multiple threads write into one temp file, which causes the problem; to fix it, separate temp files for different threads) |
| Qiskit-Terra | [#8577](https://github.com/Qiskit/qiskit-terra/issues/8577) | [#8582](https://github.com/Qiskit/qiskit-terra/pull/8582) | Randomness | Remove time_taken assertion from amplitude estimator tests |
| Qiskit-Terra | [#3434](https://github.com/Qiskit/qiskit-terra/issues/3434) | | Unknown-flakiness caused by unknown reason | Closed because it cannot be reproduced |
| Qiskit-Terra | [#3533](https://github.com/Qiskit/qiskit-terra/issues/3533) | [#3585](https://github.com/Qiskit/qiskit-terra/pull/3585) | Randomness (random numbers are generated during two qubits decomposer), resulting in different outputs | Fix Randomness (remove randomness from two_qubit_decompose) |
| Qiskit-Terra | [#4126](https://github.com/Qiskit/qiskit-terra/issues/4126) | [#4193](https://github.com/Qiskit/qiskit-terra/pull/4193) | Randomness | Fix seed |
| Qiskit-Terra | [#4606](https://github.com/Qiskit/qiskit-terra/issues/4606) | [#4656](https://github.com/Qiskit/qiskit-terra/pull/4656) | Software environment (Numpy version) | Remove specific version dependency |
| Qiskit-Terra | | [#4835](https://github.com/Qiskit/qiskit-terra/pull/4835) | Randomness (Floating point precision) | Round number |
| Qiskit-Terra | | [#6559](https://github.com/Qiskit/qiskit-terra/pull/6559) | Randomness | Fixed random number seed |
| Qiskit-Terra | [#4606](https://github.com/Qiskit/qiskit-terra/issues/4606) | [#4656](https://github.com/Qiskit/qiskit-terra/pull/4656) | Software environment (Numpy version) | Remove specific version dependency |
| Qiskit-Terra |  |   [#8820](https://github.com/Qiskit/qiskit-terra/pull/8820)        | Random Number Seed, Randomness    | Fix random seed to a fixed value  |
| Qiskit-Terra |  |  [#9023](https://github.com/Qiskit/qiskit-terra/pull/9023)<br> [#9021](https://github.com/Qiskit/qiskit-terra/pull/9021) | Randomness | Loose the thresholds of an assertion |
| Qiskit-Terra |  | [#8659](https://github.com/Qiskit/qiskit-terra/pull/8659)  | Randomness | Loose thresholds of equal test |
| Qiskit-Terra | [#8808](https://github.com/Qiskit/qiskit-terra/pull/8808)<br> [#8806](https://github.com/Qiskit/qiskit-terra/issues/8806) | [#8815](https://github.com/Qiskit/qiskit-terra/pull/8815) | Random Number Seed, Randomness | Fixed random seed, and more |
| Qiskit-Terra | [#8233](https://github.com/Qiskit/qiskit-terra/issues/8233) | [#8260](https://github.com/Qiskit/qiskit-terra/pull/8260)<br> [#8262](https://github.com/Qiskit/qiskit-terra/pull/8262) | Random Number Seed | Fixed random seed |
| Qiskit-Terra |  | [#6930](https://github.com/Qiskit/qiskit-terra/pull/6930) |       Visualization      | Add wrappers to detect incomplete file formats  |
| Qiskit-Terra | [#5217](https://github.com/Qiskit/qiskit-terra/issues/5217) | [#5599](https://github.com/Qiskit/qiskit-terra/pull/5599) | Random Number Seed  | Fixed random seed |
| Qiskit-Terra | [#5031](https://github.com/Qiskit/qiskit-terra/issues/5031) | [#5047](https://github.com/Qiskit/qiskit-terra/pull/5047) | Others | Remove hypothesis deadline  |
| Qiskit-Terra | [#3283](https://github.com/Qiskit/qiskit-terra/issues/3283) | [#3284](https://github.com/Qiskit/qiskit-terra/pull/3284) | Visualization | Update reference files |
| Qiskit-Terra | [#1225](https://github.com/Qiskit/qiskit-terra/issues/1225) | [#1226](https://github.com/Qiskit/qiskit-terra/pull/1226) | Unhandled exception | Add exception handler |
| Qiskit-Terra |  | [#7304](https://github.com/Qiskit/qiskit-terra/pull/7304) |   Random Number Seed | Fixed random number seed |
| Qiskit-Terra |  | [#8848](https://github.com/Qiskit/qiskit-terra/pull/8848) |   Random Number Seed | Fixed random seed |
| Qiskit-Terra | [#8709](https://github.com/Qiskit/qiskit-terra/issues/8709) | [#9006](https://github.com/Qiskit/qiskit-terra/pull/9006)<br> [#8627](https://github.com/Qiskit/qiskit-terra/pull/8627) | Unordered Collection | Compare key-by-key instead of the insertion order |
| Qiskit-Terra | [#8577](https://github.com/Qiskit/qiskit-terra/issues/8577) | [#8582](https://github.com/Qiskit/qiskit-terra/pull/8582) | Randomness | Remove time senstive assert |
| Qiskit-Terra | [#6188](https://github.com/Qiskit/qiskit-terra/issues/6188) | [#7682](https://github.com/Qiskit/qiskit-terra/pull/7682) | Multi-Threading | Bumping the minimum symengine version |
| Qiskit-Terra | [#5904](https://github.com/Qiskit/qiskit-terra/issues/5904) | [#6539](https://github.com/Qiskit/qiskit-terra/pull/6539) | Multi-Threading | Disables the use of parallel sphinx |
| Qiskit-Terra | [#5771](https://github.com/Qiskit/qiskit-terra/issues/5771) | [#5778](https://github.com/Qiskit/qiskit-terra/pull/5778) | Others | Ensuring all instruction objects in scheduled circuit are different |
| Qiskit-Terra |  | [#5509](https://github.com/Qiskit/qiskit-terra/pull/5509) | Software Environment | Change the deprecation shim in qiskit.util |
| Qiskit-Terra |  | [#5465](https://github.com/Qiskit/qiskit-terra/pull/5465) | Software Environment | "Expands the macOS skip on the tests to be python >= 3.8" |
| Qiskit-Aer | [#1466](https://github.com/Qiskit/qiskit-aer/issues/1466) | Closed, but no PR associated | Software Environment |  |
| Qiskit-Aer | [#1308](https://github.com/Qiskit/qiskit-aer/issues/1308) | [#1307](https://github.com/Qiskit/qiskit-aer/pull/1307) | Multi-Threading | Generate random numbers before parallization |
| Qiskit-Aer |  | [#795](https://github.com/Qiskit/qiskit-aer/pull/795) |  Randomness |  |
| Qiskit-Nature | [#849](https://github.com/Qiskit/qiskit-nature/issues/849) | [#856](https://github.com/Qiskit/qiskit-nature/pull/856) | Random Number Seed | Fix random seed |
| Qiskit-Nature | [#715](https://github.com/Qiskit/qiskit-nature/issues/715) | [#716](https://github.com/Qiskit/qiskit-nature/pull/716) | Randomness | Add approximate equal |
| Qiskit-Experiments |  | [#780](https://github.com/Qiskit/qiskit-experiments/pull/780) | Multi-Threading | Set the number of threads to 1 |
| Qiskit-ibm-runtime | [#584](https://github.com/Qiskit/qiskit-ibm-runtime/issues/584) | [#588](https://github.com/Qiskit/qiskit-ibm-runtime/pull/588) | Network | Wait until websocket finished connection |
| Qiskit-ibm-runtime |  | [#79](https://github.com/Qiskit/qiskit-ibm-runtime/pull/79) | Others | Set unique program id |
| Qiskit-ibm-provider | [#112](https://github.com/Qiskit/qiskit-ibm-provider/issues/112) | [#113](https://github.com/Qiskit/qiskit-ibm-provider/pull/113) | Others | Filter test |
| Qiskit-ibm-provider | [#293](https://github.com/Qiskit/qiskit-ibm-provider/issues/293) | [#587](https://github.com/Qiskit/qiskit-ibmq-provider/pull/587) | Unknown | |
| Qiskit-machine-learning | [#185](https://github.com/Qiskit/qiskit-machine-learning/issues/185) | Closed, but no PR associated | Unknown | Set the number of threads to 1 |
| Microsoft/qdk-python | [#319](https://github.com/microsoft/qdk-python/issues/319) | Closed, but no PR associated | Software Environment | Live test in CI |
| Microsoft/QuantumLibraries | [#398](https://github.com/microsoft/QuantumLibraries/issues/398) | [#399](https://github.com/microsoft/QuantumLibraries/pull/399) | Unhandled Exceptions | Ignore negative value |
| Microsoft/Quantum | [#62](https://github.com/microsoft/Quantum/issues/62) | [#63](https://github.com/microsoft/Quantum/pull/63) | Others | Delete space |
| Microsoft/Quantum |  | [#47](https://github.com/microsoft/Quantum/pull/47) | Software Environment | Update the version of Electron |
| Tensorflow/Quantum |  | [#453](https://github.com/tensorflow/quantum/pull/453) | Others | Fixed output manually |
| Netket/Netket |  | [#1369](https://github.com/netket/netket/pull/1369) | Software Environment | Simplified tests |
| Netket/Netket |  | [#1147](https://github.com/netket/netket/pull/1147) | Randomness | Bump assert tolerance (replace hard-coded tolerance with the error of mean) |
| Netket/Netket |  | [#724](https://github.com/netket/netket/pull/724) | Randomness | Bump assert tolerance (from atol=1e-10 to 1e-8), atol=absolute tolerance |
| Netket/Netket | |  [#840](https://github.com/netket/netket/pull/840) | Random Number Seed | Fix random seed |






