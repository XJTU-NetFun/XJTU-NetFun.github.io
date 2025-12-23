+++
title = 'LemonNFV: Consolidating Heterogeneous Network Functions at Line Speed'
date = 2023-04-17
type = 'paper'
layout = 'paper'
draft = false

research_label = ["NF"]
bibtex = """
"""
abstract = [
    "NFV has entered into a new era that heterogeneous frameworks coexist. NFs built upon those frameworks are thus not interoperable, obstructing operators from getting the best of the breed. Traditional interoperation solutions either incur large overhead, e.g., virtualizing NFs into containers, or require huge code modification, e.g., rewriting NFs with specific abstractions. We present LemonNFV, a novel NFV framework that can consolidate heterogeneous NFs without code modification. LemonNFV loads NFs into a single process down to the binary level, schedules them using an intercepted I/O, and isolates them with the help of a restricted memory allocator. Experiments show that LemonNFV can consolidate 5 complex NFs without modifying the native code while achieving comparable performance to the ideal and state-of-the-art pure consolidation approaches with only 0.7–4.3% overhead."
]
pdf = '/papers/LemonNFV/LemonNFV.pdf'
slide = '/papers/LemonNFV/LemonNFV_slide.pdf'
video = 'https://www.youtube.com/watch?v=s8sTvdLaE8Q'
publisher = "USENIX NSDI'23"
ccf = "A"
publish = "conference"

top = true
[[paper.author]]
    name = 'Hao Li'
    id = 'hli'
    url = "https://gr.xjtu.edu.cn/en/web/hao.li"
[[paper.author]]
    name = 'Yihan Dang'
    id = 'yhdang'
[[paper.author]]
    name = 'Guangda Sun'
[[paper.author]]
    name = 'Guyue Liu'
[[paper.author]]
    name = 'Danfeng Shan'
    url = "https://gr.xjtu.edu.cn/en/web/dfshan"
[[paper.author]]
    name = 'Peng Zhang'
    url = "https://gr.xjtu.edu.cn/en/web/p-zhang"


+++
