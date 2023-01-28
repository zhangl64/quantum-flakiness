# quantum-flakiness
| Project |  Repository  |               Backreport-Link                    |  Fix-Link | Categories-of-Flaky-Test |      Categories-of-Fix            |
| :---    |    :---     |                       :---:                      |  :---:    |       :---:              |              :---:                |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/8820 |           |   Random Number Seed, Assertion    | Fix random seed to a fixed value  |
| Qiskit  | Qiskit-Terra | <ul><li>https://github.com/Qiskit/qiskit-terra/pull/9023</li><li>https://github.com/Qiskit/qiskit-terra/pull/9021</li></ul> |   | Assertion | Loose the thresholds of an assertion |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/8659 |           | Assertion | Loose thresholds of equal test |
| Qiskit  | Qiskit-Terra | <ul><li>https://github.com/Qiskit/qiskit-terra/pull/8808</li><li>https://github.com/Qiskit/qiskit-terra/issues/8806</li></ul> | https://github.com/Qiskit/qiskit-terra/pull/8815 | Random Number Seed, Assertion | Fixed random seed, and more |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/8233 | <ul><li>https://github.com/Qiskit/qiskit-terra/pull/8260</li><li>https://github.com/Qiskit/qiskit-terra/pull/8262</li></ul> | Random Number Seed | Fixed random seed |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/6930 |           |       Visualization      | Add wrappers to detect incomplete file formats  |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/5217 | https://github.com/Qiskit/qiskit-terra/pull/5599 | Random Number Seed  | Fixed random seed |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/5031 | https://github.com/Qiskit/qiskit-terra/pull/5047 | Others | Remove hypothesis deadline  |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/3283 | https://github.com/Qiskit/qiskit-terra/pull/3284 | Visualization | Update reference files |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/1225 | https://github.com/Qiskit/qiskit-terra/pull/1226 | Unhandled exception | Add exception handler |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/7304 |           |   Random Number Seed | Fixed random number seed |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/8848 |           |   Random Number Seed | Fixed random seed |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/8709 | <ul><li>https://github.com/Qiskit/qiskit-terra/pull/9006</li><li>https://github.com/Qiskit/qiskit-terra/pull/8627</li></ul>  | Unordered Collection | Compare key-by-key instead of the insertion order |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/8577 | https://github.com/Qiskit/qiskit-terra/pull/8582 | Assertion | Remove time senstive assert |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/6188 | https://github.com/Qiskit/qiskit-terra/pull/7682 | Multi-Threading | Bumping the minimum symengine version |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/5904 | https://github.com/Qiskit/qiskit-terra/pull/6539 | Multi-Threading | Disables the use of parallel sphinx |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/5771 | https://github.com/Qiskit/qiskit-terra/pull/5778 | Others | Ensuring all instruction objects in scheduled circuit are different |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/5509 |           | Software Environment | Change the deprecation shim in qiskit.util |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/5465 |           | Software Environment | "Expands the macOS skip on the tests to be python >= 3.8" |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-aer/issues/1466 |           | Software Environment |  |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-aer/pull/795 |           |  Assertion |  |
| Qiskit  | Qiskit-Nature | https://github.com/Qiskit/qiskit-nature/issues/849 | https://github.com/Qiskit/qiskit-nature/pull/856 | Random Number Seed | Fix random seed |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-nature/issues/715 | https://github.com/Qiskit/qiskit-nature/pull/716 | Assertion | Add approximate equal |
| Qiskit  | Qiskit-Experiments | https://github.com/Qiskit/qiskit-experiments/pull/780 |        | Multi-Threading | Set the number of threads to 1 |
| Qiskit  | Qiskit-Qiskit-ibm-runtime | https://github.com/Qiskit/qiskit-ibm-runtime/issues/584 | https://github.com/Qiskit/qiskit-ibm-runtime/pull/588 | Network | Wait until websocket finished connection |
| Qiskit  | Qiskit-Qiskit-ibm-runtime | https://github.com/Qiskit/qiskit-ibm-runtime/pull/79 |           | Others | Set unique program id |
| Qiskit  | Qiskit-qiskit-ibm-provider | https://github.com/Qiskit/qiskit-ibm-provider/issues/112 | https://github.com/Qiskit/qiskit-ibm-provider/pull/113 | Others | Filter test |
| Qiskit  | Qiskit-qiskit-ibm-provider | https://github.com/Qiskit/qiskit-ibm-provider/issues/293 | https://github.com/Qiskit/qiskit-ibmq-provider/pull/587 | Unknown | |
| Qiskit  | Qiskit-qiskit-machine-learning | https://github.com/Qiskit/qiskit-machine-learning/issues/185 | Closed, but no PR associated | Unknown | Set the number of threads to 1 |
| Microsoft  | qdk-python | https://github.com/microsoft/qdk-python/issues/319 | No fix, automated testing | Software Environment | Live test in CI |
| Microsoft  | QuantumLibraries | https://github.com/microsoft/QuantumLibraries/issues/398 | https://github.com/microsoft/QuantumLibraries/pull/399 | Unhandled Exceptions | Ignore negative value |
| Microsoft  | Quantum | https://github.com/microsoft/Quantum/issues/62 | https://github.com/microsoft/Quantum/pull/63 | Others | Delete space |
| Microsoft  | Quantum | https://github.com/microsoft/Quantum/pull/47 | | Software Environment | Update the version of Electron |
| Tensorflow | Quantum | https://github.com/tensorflow/quantum/pull/453 |           | Others | Fixed output manually |
| Netket  | Netket | https://github.com/netket/netket/pull/1369 |           | Software Environment | Simplified tests |
| Netket  | Netket | https://github.com/netket/netket/pull/1147 |           | Assertion | Bump assert tolerance (replace hard-coded tolerance with the error of mean) |
| Netket  | Netket | https://github.com/netket/netket/pull/724 |           | Assertion | Bump assert tolerance (from atol=1e-10 to 1e-8), atol=absolute tolerance |
| Netket  | Netket | https://github.com/netket/netket/pull/840 |           | Random Number Seed | Fix random seed |










