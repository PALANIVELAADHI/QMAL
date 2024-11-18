# Quantum Multi-Agent Learning(QMAL)
This repository features the Quantum Multi-Agent Learning (QMAL) model, integrating quantum error mitigation, adaptive priority scaling, and agent synchronization. QMAL enhances learning stability, cumulative rewards, and scalability, making it ideal for advancing research in quantum multi-agent environments with datasets.

File Descriptions
# loss_function_evaluation.csv
Description: Tracks the evaluation of the loss function over training episodes.
Columns:
Episode: Training episode number.
Loss Value: Value of the loss function at the end of each episode.
Timestamp: Time of evaluation.

# network_weight_updates.csv
Description: Records updates in network weights during the training process.
Columns:
Iteration: Iteration number during training.
Weight Update Size: Magnitude of weight changes.
Convergence Metric: Measure of weight stability over iterations.

# overall_agent_performance.csv
Description: Summarizes the cumulative performance of agents over training episodes.
Columns:
Episode: Training episode number.
Cumulative Reward: Total reward collected by agents.
Error Rate: Percentage of errors encountered.
Completion Time: Duration taken for the episode.

# priority_scaling_replay_buffer.csv
Description: Details the effects of adaptive priority scaling and replay buffer operations.
Columns:
Episode: Training episode number.
Priority Factor: Scaling factor used in the replay buffer.
Buffer Utilization: Percentage of buffer used.
Reward Gain: Improvement in reward due to priority scaling.

# quantum_error_mitigation.csv
Description: Logs metrics related to quantum error mitigation strategies applied during training.
Columns:
Event ID: Identifier for quantum events.
Pre-Mitigation Error Rate: Error rate before mitigation.
Post-Mitigation Error Rate: Error rate after applying mitigation techniques.
Mitigation Efficiency: Percentage reduction in errors.

# synchronization_metric.csv
Description: Contains synchronization metrics for agents during training episodes.
Columns:
Episode: Training episode number.
Consistency Percentage: Percentage of agent actions aligned.
Synchronization Lag: Time delay between agents’ actions.
Improvement Factor: Increase in synchronization consistency over episodes.
