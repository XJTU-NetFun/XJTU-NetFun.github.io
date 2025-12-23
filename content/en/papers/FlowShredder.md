+++
title = 'FlowShredder: a Protocol-Independent in-Network Security Service in the Cloud'
date = 2024-12-07
type = 'paper'
layout = 'paper'
draft = false

research_label = []
bibtex = """
"""
abstract = [
    "Cloud services increasingly generates enormous Internet traffic. Much of it such as rich media traffic is not highly sensitive, but prefers some sort of protection. The traditional end-to-end encryption such as TLS is costly and has issues such as increased latency, while the simple anonymity solutions cannot resist traffic analysis attacks. In this paper, we propose FlowShredder, a protocol-independent and in-network service to secure such traffic in the cloud. FlowShredder aims to break the association between packets, data flow and hosts by obfuscating the packet header (some payload if needed). Without the context of flow and hosts, packets are of little value to the adversary. The operation is carried out at cloud gateways, without encrypting the payload. Its simple logic can therefore be executed within a single pipeline of the Tofino programmable switch, to ensure wire-speed performance without the scalability issue. Being protocol-independent and operating in-network at wire speed make FlowShredder a practical and generic security service to protect the cloud traffic. In addition, FlowShredder can work with end-to-end encryption such as 0-RTT TLS for enhanced protection. We implement FlowShredder in P4 switches. Experiments show that FlowShredder can effectively resist the traffic analysis attack with supervised learning techniques."
]
doi = "10.1007/978-981-96-0805-8_23"
pdf = '/papers/FlowShredder/FlowShredder.pdf'
publisher = "ICSOC 2024"
ccf = "A"
publish = "conference"
top = true
[[paper.author]]
    name = 'Bin Song'
    id = 'bsong'
[[paper.author]]
    name = 'Bin Sun'
[[paper.author]]
    name = 'Qiang Fu'
[[paper.author]]
    name = 'Hao Li'
    id = 'hli'
    url = "https://gr.xjtu.edu.cn/en/web/hao.li"
+++
