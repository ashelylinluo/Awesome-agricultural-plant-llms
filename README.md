# Awesome Agricultural & Plant Large Language Models for Grass AI-Genomics

A curated list of large language models (LLMs), foundation models, and AI agents in **agriculture, plant science, and genomics** that are relevant to **grass (Poaceae) AI-driven genomics** — including genome/DNA foundation models, crop breeding and phenotyping models, and geospatial models useful for grassland monitoring.

> **Scope & disclaimer.** This is a *curated resource*, **not a benchmark or performance ranking**, and inclusion does **not** imply endorsement. There is currently no grass-specific LLM; the models below are selected because they are *applicable or transferable* to grass genomics, breeding, and phenotyping. Several entries are products or press announcements with no peer-reviewed evidence — these are marked accordingly. **Please verify each model and its source before citing it in academic work.**

**Relevance key (to grass AI-genomics):** 🟢 High · 🟡 Medium · ⚪ Low
**Evidence key:** `paper` (preprint/journal/model card) · `product` (official site/tool) · `news` (announcement only, unverified)

---

## Contents
1. [Genome & DNA Foundation Models](#1-genome--dna-foundation-models)
2. [Plant Science & Breeding LLMs](#2-plant-science--breeding-llms)
3. [General Agricultural LLMs & Agents](#3-general-agricultural-llms--agents)
4. [Remote Sensing & Geospatial Foundation Models](#4-remote-sensing--geospatial-foundation-models)
5. [How to contribute](#how-to-contribute)
6. [How to cite](#how-to-cite)

---

## 1. Genome & DNA Foundation Models
Most directly relevant to grass genomics: sequence/DNA language models and multimodal biology models that can be applied to grass genome annotation, variant interpretation, and functional prediction.

| Model | Developer / Institution | Task / Domain | Link | Evidence | Grass relevance |
|---|---|---|---|---|---|
| AgroNT (Agro Nucleotide Transformer) | InstaDeep | Plant genome / nucleotide foundation model | https://huggingface.co/InstaDeepAI/agro-nucleotide-transformer-1b | paper | 🟢 |
| Evo2 | Arc Institute, NVIDIA, Stanford, UC Berkeley, UCSF | Biological / DNA foundation model | https://arcinstitute.org/tools/evo | paper | 🟢 |
| ChatNT | InstaDeep & BioNTech | Multimodal (DNA + language) biology model | https://huggingface.co/InstaDeepAI/ChatNT | paper | 🟢 |
| xTrimo | BioMap (百图生科) | ~100B-parameter life-science foundation model | https://xtrimo.en.biomap.com/ | product | 🟡 |

## 2. Plant Science & Breeding LLMs
Plant-functional-genomics and crop-breeding models. Note that **maize, wheat, rice and other cereals are grasses**, so cereal-breeding models are highly transferable.

| Model | Developer / Institution | Task / Domain | Link | Evidence | Grass relevance |
|---|---|---|---|---|---|
| PLLaMa | UC Santa Barbara | Open LLM for plant science | https://github.com/Xianjun-Yang/PLLaMa | paper | 🟢 |
| PlantGPT (植物GPT) | South China Agricultural Univ., Tsinghua Univ. | QA system for plant functional genomics | https://www.plantgpt.icu | product | 🟢 |
| 西南种芯-V1 (Southwest SeedCore) | Sichuan Agricultural Univ. & Boruidi | Maize intelligent-breeding LLM | https://news.sicau.edu.cn/info/1078/81476.htm | news | 🟢 |
| fomo4 wheat / crop-design breeding suite | Nanjing Agricultural Univ. | Wheat phenotyping, digital twin, breeding design | *not found* | news | 🟢 |
| 丰登 SeedLLM | Yazhouwan National Lab, Shanghai AI Lab, China Agricultural Univ. | Seed-industry / breeding LLM | https://seedllm.org.cn/ | product | 🟡 |
| BreedingGPT | Peking Univ., China Mobile | Crop-breeding LLM | http://ai4b.pku-iaas.edu.cn | product | 🟡 |

## 3. General Agricultural LLMs & Agents
Broad agricultural QA / decision-support models. Lower direct relevance to genomics, but useful as domain context.

| Model | Developer / Institution | Task / Domain | Link | Evidence | Grass relevance |
|---|---|---|---|---|---|
| 司农 Sinong | Nanjing Agricultural Univ., Nanjing Univ. of Sci. & Tech. | Open vertical agricultural LLM | https://github.com/njauzzx/Sinong | product | 🟡 |
| AgriGPT | Zhejiang Univ. | Agricultural LLM ecosystem | https://arxiv.org/abs/2508.08632 | paper | 🟡 |
| ShizishanGPT (狮子山GPT) | Huazhong Agricultural Univ. | Agricultural LLM | https://arxiv.org/abs/2409.13537 | paper | 🟡 |
| AgroGPT | MBZUAI | Agricultural vision-language model | https://github.com/awaisrauf/agroGPT | paper | 🟡 |
| AgroLLM | Pittsburg State Univ. | Agricultural chatbot | https://arxiv.org/abs/2503.04788 | paper | ⚪ |
| AgriParam | BharatGen | India-centric agricultural LLM | https://huggingface.co/bharatgenai/AgriParam | paper | ⚪ |
| Dhenu | KissanAI | India-focused agricultural LLM | https://dhenu.ai/ | product | ⚪ |
| CropWizard | NCSA / Univ. of Illinois Urbana-Champaign | Generative QA & decision support | https://uiuc.chat/cropwizard-1.5/chat | product | ⚪ |
| 神农大模型 3.0 Shennong | China Agricultural Univ. | Agricultural QA & decision reasoning | https://shennong.cau.edu.cn/ | product | ⚪ |
| 天工开悟 Kwoo | Harbin Institute of Technology | Agricultural QA | https://www.tgkwai.com/ | product | ⚪ |
| 奇稷 QeeG | Beijing Academy of Agriculture & Forestry Sciences | Multimodal agricultural LLM | http://www.qeeg.org.cn/front | product | ⚪ |
| 农科小智 V2.0 | Beijing Academy of Agriculture & Forestry Sciences | Multimodal agricultural LLM | https://llm.bjzntd.com/ | product | ⚪ |
| CropWise AI | Syngenta | Generative AI system | https://www.cropwise.com/ | product | ⚪ |
| Taranis Ag Assistant | Taranis | Generative AI agronomy agent | https://go.taranis.com/ag-assistant/ | product | ⚪ |
| 九壤耘星 Jiurang Yunxing | Northwest A&F Univ. & Huawei | Domestic-compute agricultural LLM | https://news.sciencenet.cn/htmlnews/2025/8/549311.shtm | news | ⚪ |
| 后稷 Houji | Northwest A&F Univ. | Agricultural LLM (sub-app 御锈 = wheat stripe rust) | https://news.nwafu.edu.cn/mtwx/6f0d13e9ae52448db81a41e03c68078a.htm | news | 🟡 |
| iMAP | Sinochem | Integrated crop-planting LLM | https://www.sinochemagri.com/sinochemagri/news/xwsd/2025/8/I1409836524828098560.html | news | ⚪ |
| 万象耕耘 Wanxiang Gengyun | China Mobile | Agricultural LLM | http://www.sasac.gov.cn/n2588025/n2588124/c33329690/content.html | news | ⚪ |
| 稷睿 Jirui | SenseTime | Crop-planting decision LLM | *not found* (documented in a CSAE journal review, 2025) | news | ⚪ |
| 弘农 Hongnong | iFlytek & Henan Agricultural Univ. | Agricultural AI platform | https://www.henau.edu.cn/info/1002/42341.htm | news | ⚪ |
| 农业知识大模型 | Chinese Academy of Agricultural Sciences, CNKI | General agricultural LLM | *not found* | news | ⚪ |
| Bayer E.L.Y. | Bayer Crop Science | Crop-protection small language model (SLM) | https://www.bayer.com/en/agriculture/ai-for-agriculture | product | ⚪ |
| Corteva CAIRL (Project CARL) | Corteva | GenAI agronomy assistant | https://investors.corteva.com/static-files/58e1f9f4-bad4-42da-ba42-cf050c4a238d | news | ⚪ |

## 4. Remote Sensing & Geospatial Foundation Models
Useful for grassland mapping, biomass estimation, and field phenotyping.

| Model | Developer / Institution | Task / Domain | Link | Evidence | Grass relevance |
|---|---|---|---|---|---|
| AgroMind | Sun Yat-sen Univ., Tsinghua Univ. | Agricultural remote-sensing scene understanding | https://rssysu.github.io/AgroMind/ | paper | 🟡 |
| SkySense | Wuhan Univ. | Multimodal remote-sensing foundation model | https://github.com/Jack-bo1220/SkySense | paper | 🟡 |
| EarthGPT | Beijing Institute of Technology | Remote-sensing general model | https://github.com/wivizhang/EarthGPT | paper | 🟡 |
| Prithvi | NASA, IBM | Geospatial AI foundation model | https://huggingface.co/ibm-nasa-geospatial | paper | 🟡 |
| Clay | Clay Foundation | Earth-observation foundation model | https://madewithclay.org/ | product | 🟡 |
| GeoChat | MBZUAI | Geography-aware multimodal LLM | https://mbzuai-oryx.github.io/GeoChat/ | paper | ⚪ |
| GeoGPT | Zhejiang Lab | Geoscience foundation model | https://geogpt.zero2x.org.cn/ | product | ⚪ |
| 坤元 Sigma Geography | CAS, Inst. of Geographic Sciences & Natural Resources Research | Multimodal geoscience LLM | https://igsnrr.cas.cn/news/picnews/202409/t20240920_7374237.html | news | ⚪ |
| 農耕大模型 | CAAS, Inst. of Agricultural Resources & Regional Planning | Farmland monitoring & cropland protection | *not found* | news | ⚪ |

---

## How to contribute
Contributions are welcome. To suggest a model, correction, or link:
1. Open an Issue or submit a Pull Request.
2. Use the table format above and include: **model name, developer/institution, task/domain, link, evidence type** (`paper` / `product` / `news`), and a one-line justification for grass relevance.
3. Prefer official links and peer-reviewed sources. If no official source exists, mark the evidence as `news` and leave the link as `not found`.

See `CONTRIBUTING.md` for details.

## How to cite
If you find this list useful, please cite it as:

```
[Author(s)]. Awesome Agricultural & Plant LLMs for Grass AI-Genomics. GitHub repository, [year]. https://github.com/<your-username>/Awesome-agricultural-plant-llms
```

*(For a stable, versioned, citable reference, archive a release via [Zenodo](https://zenodo.org/) to obtain a DOI.)*

---

*Last updated: 2026-06-11. Most entries verified against official institutional / company sources on this date. Entries still marked `not found` (e.g. fomo4 wheat, 农业知识大模型, 農耕大模型, 稷睿) could not be linked to a verifiable primary source and should be treated with caution. All `news`-tagged entries are press/launch announcements without peer-reviewed evidence.*
