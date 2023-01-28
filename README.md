# quantum-flakiness
| Project |  Repository  |               Backreport-Link                    |  Fix-Link | Categories-of-Flaky-Test |      Categories-of-Fix            |
| :---    |    :---:     |                       :---:                      |  :---:    |       :---:              |              :---:                |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/8820 |           |   Random seed, assert    | Fix random seed to a fixed value  |
| Qiskit  | Qiskit-Terra | <ul><li>https://github.com/Qiskit/qiskit-terra/pull/9023</li><li>https://github.com/Qiskit/qiskit-terra/pull/9021</li></ul> |   | Assertion | Loose the thresholds of an assertion |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/8659 |           | Assertion: assertImagesAreEqual() | Loose thresholds of equal test |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/8659 |           | Assertion: assertImagesAreEqual() | Loose thresholds of equal test |
| Qiskit  | Qiskit-Terra | <ul><li>https://github.com/Qiskit/qiskit-terra/pull/8808</li><li>https://github.com/Qiskit/qiskit-terra/issues/8806</li></ul> | https://github.com/Qiskit/qiskit-terra/pull/8815 | Random seed, assertEqual | Fixed random seed, and more |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/8233 | <ul><li>https://github.com/Qiskit/qiskit-terra/pull/8260</li><li>https://github.com/Qiskit/qiskit-terra/pull/8262</li></ul> | Random seed | Fixed random seed |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/6930 |           |       Visualization      | Add wrappers to detect incomplete file formats  |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/5217 | https://github.com/Qiskit/qiskit-terra/pull/5599 | Random seed  | Fixed random seed |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/5031 | https://github.com/Qiskit/qiskit-terra/pull/5047 | "Others: hypothesis deadline (set to default value by mistake) https://hypothesis.readthedocs.io/en/latest/settings.html" | Remove hypothesis deadline  |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/3283 | https://github.com/Qiskit/qiskit-terra/pull/3284 | Visualization (image comparison) | Update reference files |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/1225 | https://github.com/Qiskit/qiskit-terra/pull/1226 | Unhandled exception: network/server connection (to https://qvisualization.mybluemix.net/) | Add exception handler |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/7304 |           |   Random seed | Fixed random number seed |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/8848 |           |   Random seed | Fixed random seed |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/8709 | <ul><li>https://github.com/Qiskit/qiskit-terra/pull/9006</li><li>https://github.com/Qiskit/qiskit-terra/pull/8627</li></ul>  | Python: non-deterministic order of qubits; Python's implementation of dictionary is in an uncontrolled collection | Compare key-by-key instead of the insertion order |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/8577 | https://github.com/Qiskit/qiskit-terra/pull/8582 | Assert | Remove time senstive assert |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/6188 | https://github.com/Qiskit/qiskit-terra/pull/7682 | Multi-threading-multiprocessing (fork() function) | Bumping the minimum symengine version |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/5904 | https://github.com/Qiskit/qiskit-terra/pull/6539 | Multi-threading-parallel builds | Disables the use of parallel sphinx |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/issues/5771 | https://github.com/Qiskit/qiskit-terra/pull/5778 | Others: incorrect durations in scheduled circuit | Ensuring all instruction objects in scheduled circuit are different |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/5509 |           | Environmental issue, i.e., consistency issue (backwards compatibility) | Change the deprecation shim in qiskit.util |
| Qiskit  | Qiskit-Terra | https://github.com/Qiskit/qiskit-terra/pull/5465 |           | Environmental issue (software/library versions) | "Expands the macOS skip on the tests to be python >= 3.8" |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-aer/issues/1466 |           |  Environmental issue (qiskit-terra)  |  |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-aer/pull/795 |           |  Assert (changed tolerance to dynamic)  |  |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-nature/issues/849 | https://github.com/Qiskit/qiskit-nature/pull/856 | Random seed | Fix random seed |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-nature/issues/715 | https://github.com/Qiskit/qiskit-nature/pull/716 | Assert: exact equal may lead to flaky test | Add approximate equal |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-experiments/pull/780 |           | Multi-threading parallel execution | Set the number of threads to 1 |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-ibm-runtime/issues/584 | https://github.com/Qiskit/qiskit-ibm-runtime/pull/588 | Network/server issue (sometime network too slow) | Wait until websocket finished connection |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-ibm-runtime/pull/79 |           | Others: program is not unique | Set unique program id |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-ibm-provider/issues/112 | https://github.com/Qiskit/qiskit-ibm-provider/pull/113 | Others: test fall in wrong category | Filter test |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-ibm-provider/issues/293 | https://github.com/Qiskit/qiskit-ibmq-provider/pull/587 | Unknown | |
| Qiskit  | Qiskit-Aer | https://github.com/Qiskit/qiskit-machine-learning/issues/185 | Closed, but no PR associated | Unknown | Set the number of threads to 1 |








