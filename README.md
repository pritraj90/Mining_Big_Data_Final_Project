Abstract

The Centers for Medicare and Medicaid Services (CMS) have recently released a dataset containing all medications prescribed under Medicare Part D throughout 2013. The dataset includes specific information regarding physicians and other health care providers who have written prescriptions covered by Medicare Part D, as well as the types of medications, quantities, costs and other relevant data. In this report, I demonstrate the advantages of using parallel processing when querying relatively large datasets by comparing run times between a three-node Hadoop cluster to a single machine. Additionally, I compare performance between Hive and Pig on both machine setups. The same queries were executed on both the single machine as well as the three-node cluster, resulting in a reduction of run times between 40% and 58% when leveraging the parallel processing capabilities of the Hadoop cluster. With regard to the comparison of Hive and Pig, results show Hive outperformed Pig on every query in terms of absolute run times, regardless of the machine setup. Nevertheless, Pig tended to have a greater percentage improvement in run time when going from a single machine to a three-node cluster, as compared to the improvement realized with Hive.
