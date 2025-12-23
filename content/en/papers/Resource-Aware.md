+++
title = ' Resource-Aware Intent Compilation for Virtual Private Cloud '
date = 2025-11-16
type = 'paper'
layout = 'paper'
draft = false

research_label = []
bibtex = """
"""
abstract = [
    " Migrating enterprise IT services to the cloud is becoming a trend. However, configuring virtual networks in the cloud is a costly and error-prone task. In this paper, we model the problem of VPC intent compilation and prove that the problem is NP-hard. We design a heuristic method to automatically translate the intents into VPC configurations. To facilitate the heuristic, we propose an algorithm for finding small cuts (AFSC) based on the Louvain algorithm, which is used to separate subnets across VPCs. The generated configurations find an equilibrium between maximizing the network performance and minimizing the resource consumption. Experimental results show that our heuristic method reaches 100% correctness, compiles large intent sets from real-world networks with hundreds of subnets and thousands of intents in under a minute, and improves the effectiveness by ∼2.8× in terms of resource consumption relative to network performance. "
]
doi = "10.1109/ISCC61673.2024.10733611"
pdf = '/papers/Resource-Aware/Resource-Aware.pdf'
publisher = "ISCC"
ccf = "A"
publish = "conference"
top = true
[[paper.author]]
    name = 'Jia Zhang'
    id = 'jzhang'
[[paper.author]]
    name = 'Wanyue Cao'
[[paper.author]]
    name = 'Qiang Fu'
[[paper.author]]
    name = 'Hao Li'
    id = 'hli'
    url = "https://gr.xjtu.edu.cn/en/web/hao.li"

+++
