## Analysis

The results show that measured RTT values are consistently higher than the theoretical minimum RTT for all cities. This is expected because the theoretical calculation assumes that data travels along a direct path at the speed of light in fiber, without any delays. In reality, network packets traverse complex routes that include multiple routers, indirect paths, and potential congestion, all of which contribute to increased latency.

Figure 1 demonstrates that the measured RTT is typically between 1.5 to 4 times greater than the theoretical minimum. The difference is especially large for closer cities such as London, where routing inefficiencies and network overhead dominate. For farther cities like Sydney, the measured RTT is closer to the theoretical value because propagation delay becomes the dominant factor over long distances.

Figure 2 shows a general positive correlation between distance and RTT, confirming that distance is a major contributor to latency. However, the relationship is not perfectly linear, indicating that other factors such as routing paths, infrastructure quality, and network congestion also play significant roles.

Overall, the experiment highlights that while the speed of light sets a fundamental lower bound on latency, real-world network performance is heavily influenced by additional practical constraints.