+] Running 9/9
 ✔ Network simple-taiko-node_default                                                                                                       Created                0.1s
 ✔ Container simple-taiko-node-l2_execution_engine-1                                                                                       Started                0.3s
 ✔ Container simple-taiko-node-zkevm_chain_prover_rpcd-1                                                                                   Started                0.3s
 ✔ Container simple-taiko-node-taiko_client_driver-1                                                                                       Started                0.3s
 ! zkevm_chain_prover_rpcd Your kernel does not support swap limit capabilities or the cgroup is not mounted. Memory limited without swap.                        0.0s
 ✔ Container simple-taiko-node-prometheus-1                                                                                                Started                0.3s
 ✔ Container simple-taiko-node-taiko_client_prover_relayer-1                                                                               Started                0.3s
 ✔ Container simple-taiko-node-taiko_client_proposer-1                                                                                     Started                0.3s
 ✔ Container simple-taiko-node-grafana-1                                                                                                   Started                0.2s
root@vm1799501:~/simple-taiko-node# cd simple-taiko-node
-bash: cd: simple-taiko-node: No such file or directory
root@vm1799501:~/simple-taiko-node# docker-compose down && docker-compose up -d
[+] Running 8/8
 ✔ Container simple-taiko-node-grafana-1                      Removed                                                                                             0.8s
 ✔ Container simple-taiko-node-taiko_client_prover_relayer-1  Removed                                                                                            10.9s
 ✔ Container simple-taiko-node-taiko_client_proposer-1        Removed                                                                                            10.8s
 ✔ Container simple-taiko-node-prometheus-1                   Removed                                                                                             0.6s
 ✔ Container simple-taiko-node-zkevm_chain_prover_rpcd-1      Removed                                                                                            10.7s
 ✔ Container simple-taiko-node-taiko_client_driver-1          Removed                                                                                            10.9s
 ✔ Container simple-taiko-node-l2_execution_engine-1          Removed                                                                                             3.2s
 ✔ Network simple-taiko-node_default                          Removed                                                                                             0.2s
[+] Running 5/5
 ✔ zkevm_chain_prover_rpcd Pulled                                                                                                                                 1.2s
 ✔ taiko_client_driver Pulled                                                                                                                                     1.6s
 ✔ l2_execution_engine Pulled                                                                                                                                     1.3s
 ✔ taiko_client_prover_relayer Pulled                                                                                                                             1.6s
 ✔ taiko_client_proposer Pulled                                                                                                                                   1.3s
[+] Building 0.0s (0/0)                                                                                                                                 docker:default
[+] Running 9/9
 ✔ Network simple-taiko-node_default                                                                                                       Created                0.2s
 ✔ Container simple-taiko-node-l2_execution_engine-1                                                                                       Started                0.3s
 ✔ Container simple-taiko-node-zkevm_chain_prover_rpcd-1                                                                                   Started                0.3s
 ! zkevm_chain_prover_rpcd Your kernel does not support swap limit capabilities or the cgroup is not mounted. Memory limited without swap.                        0.0s
 ✔ Container simple-taiko-node-taiko_client_driver-1                                                                                       Started                0.2s
 ✔ Container simple-taiko-node-prometheus-1                                                                                                Started                0.4s
 ✔ Container simple-taiko-node-taiko_client_prover_relayer-1                                                                               Started                0.4s
 ✔ Container simple-taiko-node-taiko_client_proposer-1                                                                                     Started                0.4s
 ✔ Container simple-taiko-node-grafana-1                                                                                                   Started                0.3s
root@vm1799501:~/simple-taiko-node#
что это значит?


Этот вывод является частью командного интерфейса Docker и Docker Compose, который используется для управления контейнерами и приложениями, запущенными в контейнерах. 
