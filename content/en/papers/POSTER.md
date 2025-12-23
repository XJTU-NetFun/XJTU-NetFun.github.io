+++
title = 'POSTER: Bring I-Cache to Light in Data Plane Applications'
date = 2024-08-05
type = 'paper'
layout = 'paper'
draft = false

research_label = []
bibtex = """
"""
abstract = [
    "Modern data plane applications are usually with large code, causing the i-cache to miss frequently during execution. To this end, we apply a new execution model on these applications that splits them into i-cache-friendly stages, and reuse the code of each stage on multiple packets. Experiments on snort3 show that i-cache misses are reduced by 72.2%, and throughput increases by 25.0%."
]
doi = "10.1145/3672202.3673724"
pdf = '/papers/POSTER/POSTER.pdf'
publisher = "SIGCOMM Posters and Demos 2024"
ccf = "A"
publish = "conference"
top = true
[[paper.author]]
    name = 'Yihan Dang'
    id = 'yhdang'
[[paper.author]]
    name = 'Ze Xia'
    id = 'zxia'
[[paper.author]]
    name = 'Hao Li'
    id = 'hli'
    url = "https://gr.xjtu.edu.cn/en/web/hao.li"

+++
