## Louvre Emergency Evacuation Optimization Plan

### Meritorious Winner of 2019 Interdisciplinary Context in Modeling

Since the 21st century, terrorist attacks have intensified. As a famous attraction in France and the world, the research on Louvre's emergency evacuation program has far-reaching guiding significance for the establishment of emergency evacuation programs for large public facilities in the world.

In order to establish an emergency evacuation model, we analyze the psychological and behavioral characteristics of tourists, the impact of different disasters, and the impact of different population characteristics and density. For the emergency evacuation problem of multi-floor complex buildings, our model is divided into intra-floor models and inter-floor models.

Our intra-floor model consists of the security response zone division model and real-time path planning model based on network.

In the Security Response Zone Division Model, the size of the security response zone(SRZ) is related to the number of visitors in the area and the properties of the passage. We use the goal planning method to calculate the total evacuation time as our objective function to determine the size of the SRZ corresponding to different exits or stairways. Meanwhile, calculating the objective function, we could get the minimum total time for evacuation in a floor.

**In the Real-time Path Planning Model Based on Network, the doors are regarded as the nodes. We define the congestion factor, the risk factor, and the corridor length as three factors that influence the evacuation of tourists. The equivalent length, which is based on the three factors, can more accurately reflect the time and the safety of the evacuation of tourists. Therefore, the optimal path with the minimum equivalent length is chosen as the target.**

![Transforms in Escape Network](https://raw.githubusercontent.com/TimeLovercc/img/master/image-20200717153355952.png)

For the establishment of the inter-floor model, the structure of the network is used to calculate the flow distribution of the human flow after passing through different nodes and edges. According to the real-time traffic time image, we can effectively avoid the occurrence of over-aggregated during the evacuation process.

Finally, we offer a range of solutions that can be combined with our emergency evacuation program to deal with difficult situations, such as how to effectively evacuate small language visitors, how to arrange rescue workers to enter the venue as soon as possible, and so on.

![Model Structure](https://raw.githubusercontent.com/TimeLovercc/img/master/image-20200717152842312.png)

